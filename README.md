# pwssite
Privacy Workshop Webサイト管理用です
- 運用方法
  - [このスライド](https://docs.google.com/presentation/d/1VPrXKw8AN9LVo-EXei2zOkcJoQwn1LSfwvPKT-2-5lA/edit)を見ましょう
# フォルダ構成
- 2019
  - PWS2019のサイト
  - 2018 以前は管理していません
- .circleci
  - circleciの設定

# ブランチ
- master
  - 本番の[IWSECサーバ](https://www.iwsec.org/pws/2019/)用
  - masterにcommitした内容は、circleci で自動的に本番にデプロイされるので注意です
- gh-pages
  - テスト用
  - 本番にデプロイする前に、gh-pagesにpushしましょう
  - [github-pages](https://pwscup.github.io/pws2019site)で確認しましょう
- その他
  - 自由

# ワークフロー
  - gh-pagesからbranchを切る
  - ローカルでcommitする
  - gh-pagesにマージして、pushする
  - [github-pages](https://pwscup.github.io/pws2019site)で確認する
  - masterにマージして、本番の[IWSECサーバ](https://www.iwsec.org/pws/2019/)を確認する

# 備考
  - サイズの大きなデータは、githubには置けないので注意
    - 2019 は 2019/data/ をgitignoreしています data以下はscpしています

# 詳細は
- [PWS Slack](https://pwscup.slack.com)で質問してください
