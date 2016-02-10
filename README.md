# README

## Directory

- build/ : ビルドファイル（chromeに指定するディレクトリ）
- metadata/ : manifest.jsonやアイコン
- src/ : ソースコード
- lib/ : 外部ライブラリ
  - TODO: npmを使ってインストールし、node_module/配下にあるものを使うようにしたい（バージョンアップの手間を減らすため）

## develop

```sh
$ npm install
$ gulp build
$ gulp watch
```
