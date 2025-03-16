## ディレクトリ構成

```
.
├── README
├── bun.lock
├── eslint.config.mjs
├── index.html
├── package.json
├── public -> ./resources/public    ... ローカルサーバー実行時のリソース格納先
├── resources                       ... リソース置き場
│   ├── README
│   └── public                      ... 実際に配信されるリソース
│       ├── assets
│       │   ├── bunny.png
│       │   └── logo.svg
│       ├── favicon.png
│       └── style.css
├── src
│   ├── main.ts
│   └── vite-env.d.ts
├── tsconfig.json
└── vite.config.ts
```

## ローカルサーバー実行

```sh
bun run dev
```

## ビルド

```sh
bun run build
```
