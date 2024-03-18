# 更新方法
このホームページの更新方法をまとめます。

このホームページは[jekyll](https://jekyllrb-ja.github.io/)および [minimal mistakes](https://github.com/mmistakes/minimal-mistakes)を利用して構築されています。


## 開発環境の構築
DevContainerまたはCodespacesを利用するのが簡単です。

### codespaces
1. Githubのこのリポジトリにアクセスします。
1. 「< > Code」ボタンから、Codespacesを作成します。

## 開発サーバ
`bundle exec jekyll server` で開発サーバが立ち上がります。  
開発サーバを立ち上げると `localhost:4000` でホームページが確認できるようになります。

## コンテンツの配置
`_pages` ディレクトリ以下に、各種ページのファイルがあります。

`_posts` ディレクトリ以下にブログページがあります。  
`_posts` 以下に、 `<日付>-<名前>.md`というファイルを作成すると自動的にブログ記事として扱われます。

## デプロイ
`main` ブランチの内容が自動的にホームページに反映されます。