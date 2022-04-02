# gitbook

## 環境構築

```sh
npm i -g gitbook-cli
gitbook install
```

## 動作環境

以下のコマンドを実行すると、_bookにbuildファイルが作成され、http://localhost:4000 から確認できる
```sh
gitbook serve
```

## 変更の反映

以下のコマンドを実行すると、docsにbuildファイルが作成されるので、buildしたものをmasterにpushする
```sh
gitbook build . docs
```
