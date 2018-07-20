---
layout: page
title: このwikiの書き方
permalink: /howtowrite/
published: true
---

## githubアカウントを作る
[https://github.com/join](https://github.com/join)

## グループへ招待してもらう
twitter [@esctrax](https://twitter.com/esctrax)宛にリプライもしくはダイレクトメッセージ  
もしくはesctrax[at]gmail.com宛に直接参加希望のgithubアカウントをご連絡下さい

![スクリーンショット 2018-07-19 13.12.37.png]({{site.baseurl}}/wiki/スクリーンショット 2018-07-19 13.12.37.png)

こんな感じの招待メールがgithubから届きますので、  
"Join kdj-wiki" をクリックして認証手続きに進んで下さい。

## prose.ioを使って wiki/ 以下で.mdファイルを作成/編集する
記事はmarkdown記法で書きます。  
記法については下記のような記事が参考になると思います。  
[Markdown記法 チートシート @Qiita](https://qiita.com/Qiita/items/c686397e4a0f4f11683d)

### prose.ioへのログイン
[http://prose.io](http://prose.io) を初めて使う方はここでも認証が必要です。  
![スクリーンショット 2018-07-19 13.14.39.png]({{site.baseurl}}/wiki/スクリーンショット 2018-07-19 13.14.39.png)

このとき、Organization accessに kdj-wikiが入ってることを確認して下さい!

### 既存の記事の編集
ファイル構成は下記のようになっています

```
├─ index.md → トップページ
└── wiki
    ├── howtowrite.md → この記事
    | :
    └── *.md 
```
prose.ioのファイルツリーから編集したい記事を選ぶか、  
公開されている記事の "Edit with Prose.io"のリンクから編集画面に入って下さい。


### 新規記事の作成
新規に記事を作成する場合は、wiki/以下に.mdファイルを追加して下さい。
下記のテンプレートを参考にファイルを作成して下さい。
```
---
layout: page
title: ここにタイトルを記述
permalink: /記事のパス名をここに記述/
---
記事本文
```

## 修正をコミットする
記事の編集/作成が完了しましたら、  
編集画面右のフロッピーマークでコミットして下さい。  
コミットの際は編集内容をダイジェストで記述してもらえると履歴がわかりやすくなります。
