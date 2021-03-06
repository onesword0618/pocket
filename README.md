# <center>![pocket](./docs/logo/pocket.png)</center>

![GitHub](https://img.shields.io/github/license/onesword0618/pocket?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/onesword0618/pocket?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/onesword0618/pocket?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/onesword0618/pocket?style=plastic)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/onesword0618/pocket?style=plastic)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/onesword0618/pocket?style=plastic)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=plastic)](https://github.com/prettier/prettier)
[![code checker: eslint](https://img.shields.io/badge/checker-eslint-blue?style=plastic)](https://github.com/eslint/eslint)

## Description

このアプリケーションは、利用者の家計の記録を補助します。

これにより、利用者の消費活動の記録と、予算を組むことができます。

その結果、利用者の消費活動の振り返りと計画の修正を立てることができます。

## Modeling

- [USECASE](./docs/modeling/usecase.md#設計)

## Usage

詳細なコマンドは以下の scripts のセクションをご覧ください。

[package.json](./package.json)

dev : npm run dev ... devtools && electron を起動

clean : npm run clean ... 古いコンパイルしたリソースを削除

build : npm run build ... 配布用資材の構築を実施

serve : npm run serve ... electron 起動

start : npm start ... clean -> build -> serve の順番でコマンドを起動

storybook : npm storybook ... storybook を起動

### Distribution

Windows / Linux - Ubuntu

docker を起動して、その中で、コンパイルを実施する

## License

- [MIT](./LICENSE)

## Author

- [Twitter](https://twitter.com/onesword0618)
