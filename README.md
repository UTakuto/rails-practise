# 📦rails-practice
>Dockerで動かすRuby on Railsの練習用プロジェクト

<br>

## 🛠使用技術・バージョン
|項目|バージョン|
|-----|-----|
|Ruby|3.2.8|
|Ruby on Rails|7.1.5.1|
|MySQL|8|
|Docker|最新版|
|Docker compose|最新版|


## 🚀 起動方法

1. リポジトリをクローン
    ```
     git clone https://github.com/UTakuto/rails-practise.git
    ```
2.  Dockerでビルド＆起動
     ```
     docker compose build
     docker compose up
     ```
3.  Railsにアクセス
     ```
      http://localhost:3010
     ```



<br>

## ディレクトリ構成と説明文
>誰でもわかりやすいように書かれています(Chat GPTより)
```
rails-practise
├── app                 # メインのアプリケーションロジック（MVCのView, Controllerなど）
├── bin                 # 実行ファイル（rails コマンドなど）
├── config              # 設定ファイル（ルーティングやDB設定）
├── db                  # データベース関連（マイグレーションなど）
├── lib                 # 外部モジュールやライブラリ
├── log                 # ログファイル（.gitignoreで無視）
├── public              # 静的ファイルを配置する場所（HTMLや画像など）
├── storage             # ActiveStorage用（画像アップロードなど）
├── test                # テストコード
├── tmp                 # 一時ファイル
├── vendor              # 外部ライブラリ（基本使わない）
├── config.ru           # Rack起動設定ファイル（Pumaなど）
├── docker-compose.yml  # Docker構成ファイル（MySQL、Railsの連携など）
├── Dockerfile          # Rails用のDockerイメージ定義
├── Gemfile             # 使用するgemの一覧（RailsやMySQLなど）
├── Gemfile.lock        # gemの依存バージョン固定ファイル
├── Rakefile            # タスク実行用スクリプト（rails db:migrateなど）
└── README.md           # このファイル
```
