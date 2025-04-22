# 目次

## 本プロジェクトについて

### 目標(Goal)

- 要件定義をなるべくシンプルにしつつ、他チームでも流用できるような技術基盤を固めることを目標とする(技術が主役)。
  - 提供はオンライン機能を想定(他の提供方法も必要なら鋭意検討)

### 手段(Means)

- バックエンド

  - 言語
    - Java(Version:17)
  - FW
    - Spring Boot(3.x 系)
  - ビルドツール
    - Maven
  - DB

    - MySQL
    - H2Database(テストデータの投入に使用)
    - Redis(セッション情報のキャッシュに使用)

  - ログ
    - Logback
  - 認証
    - Google + OAuth
  - その他依存関係
    - ORM Mapper
      - MyBatis
    - Migration
      - Flyway
    - セキュリティ
      - Spring Security

- フロント

  - React を使用予定

- 環境

  - dev 環境
    - 構成
      - Java の実行マシン
        - Eclipse
      - リクエストを処理するマシン
        - フロント CLI
      - DB を乗せるマシン
        - Docker
    - 目的
      - 素早く開発できるようにするため
  - docker 環境
    - 構成
    - 目的
  - stg 環境
    - 構成
    - 目的
  - prd 環境
    - 構成
    - 目的
      > docker 環境：初期開発用・開発時の検証、レビューに使用

## Docs

### ネットワーク構成

☞ ネットワーク構成図を参照(Google SpreadSheet にて作成予定)

### 画面遷移図

☞ 画面遷移図を参照(Google SpreadSheet にて作成予定)

### コーディング規約

☞ コーディング規約を参照(Google SpreadSheet にて作成予定)

## 実装について

### バックエンド

☞owproject_backend

### フロントエンド

☞owproject_frontend

### 環境(dev,docker)

☞owproject_env
