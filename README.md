# 環境構築

-   ルートディレクトリにて以下を実行

```
docker-compose up -d
```

-   コンテナが起動したら以下を実行し app コンテナに入る

```
docker-compose exec app bash
```

-   app コンテナに入ることができたら依存ファイルのインストールを行う

```
composer install
npm install
```

# トラブルシューティング

-   随時追加予定

# ドキュメント

-   追加予定
