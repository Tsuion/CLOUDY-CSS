# CLOUDY-CSS
ガキの暇つぶしです。碌なもんじゃござぁせん。
## 概要
https://wowane.f5.si にも使用されている、曇ったような色合いと丸みのあるデザインが特徴的なCSS Framework。  
現代人の美的感覚に合わせた曲線と立体感はどんな用途のサイトにも適応します(嘘)  
もちろんレスポンシブにも対応です。
## インストール(笑)
インストールとかは不要です。 以下のコードをHTMLの`<head>`にコピペしてください。 
解説しておくと、最初の３行はフォントのインポートで４行目がCSS本体のインポートになっています。

```
 <link rel="preconnect" href="https://fonts.googleapis.com">   
 <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>   
 <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300&family=M+PLUS+Rounded+1c:wght@300&display=swap" rel="stylesheet">  
 <link rel="stylesheet" href="https://github.com/Tsuion/CLOUDY-CSS/blob/ebd6083bcbcf6978e3679908f2291e31fd6b265c/css/cloudy.css" />
 ```
<red>このコードは、かなり高頻度で変更されます。変更された際にはお知らせしますので、頻繁な確認お願い致します。</red>

## 使えるclass
- `<div class="header"></div>`    
ヘッダーの下敷きみたいなやつだよ
- `<div class="header-logo"></div>`  
ヘッダーのタイトルみたいなアレだよ
- `<div class="header-list"></div>`  
サブページに飛ぶやつだよ。Githubでいうところの"Pull requests Issues Marketplace Explore"ってやつのことだよ。リスト形式になってるから、`<ul><li>`で囲もうね。
- `<div class="contents-box"></div>`  
見出し。アニメーションついてるよ。
- `<div class="contents"></div>`  
`contents-box`を含む1セクションをこれで囲んでほしいと思ってるよ。でも一番上のセクションを囲むと表示が狂っちゃうかもしれないよ。
- `<div class="btn"></div>`  
ボタンだよ。ボタンじゃないけどボタンだよ。
- `<div class="footer"></div>`  
著作権表記とかしやすいよ。ただ上に線がびーって引かれるだけだよ。
- `<div class="main"></div>`  
ヘッダーフッター以外の要素をこれで囲んでほしいと思ってるよ。そうしないと後悔するよ。

## 利用に関する諸注意
- **ずぇーったい著作権表記をしてね。荻窪りょうとの約束だよ  具体的には、`©wowane 2022/CLOUDY-CSS`とフッター部分に表記してください。**
- 利用は自己責任、報告は不要
- 編集、二次配布は自由、報告は不要
- 別に私のサイトにこのCSSをそのまま使ってるわけじゃないです。基本はこれですが特別仕様のものとなっております。
