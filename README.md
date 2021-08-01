# VOICEVOX

## 環境構築

```
npm install
```

## 実行

`.env.production`をコピーして`.env`を作成し、`ENGINE_PATH`に`voicevox_engine`があるパスを指定します。
とりあえず製品版 VOICEVOX のディレクトリのパスを指定すれば動きます。

```
npm run electron:serve
```

## ビルド

```
npm run electron:build
```

## Lint

```
npm run lint
```
