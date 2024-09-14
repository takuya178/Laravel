## 環境構築
```php
// src配下にLaravelアプリケーションが作成されている場合は不要
make create-project
```
```php
// src配下にLaravelアプリケーションが作成されている場合はこちらのコマンド
make install
```

## システムの説明
githooksを採用しており、git commit時に下記2つ解析が自動で行われます
- [Laravel pint](https://readouble.com/laravel/9.x/ja/pint.html)：コードスタイルの自動整形ツール
- [Larastan](https://github.com/larastan/larastan)：静的解析ツール


