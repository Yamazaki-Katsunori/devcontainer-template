# devcontainer-template
devcontainerを利用した開発環境のテンプレートリポジトリ作成

## 利用方法
1, GitHubにて、リポジトリを新規作成
2, 参照するテンプレートリポジトリの選択をこのテンプレートに指定して作成
3, 以降、作成したディレクトリ固有の設定にカスタマイズする

## デフォルトの設定に関して
### docker 各種コンテナ

### DBコンテナ
- MySql のDockerfile
- my.cnf mysqlの設定ファイル

### webserver
- nginx のDockerfile

### app
- tarなどの必要最低限のパッケージの Dockerfile


