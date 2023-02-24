# ICON Search System

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## ツール概要

検索条件に従い、学習指導要領 DS と学習指導要領解説 DS を検索する。
検索した学習指導要領 DS の内容を表示する。

## 動作保証環境

ブラウザ：Google Chrome, Microsoft Edge, Firefox, Internet Explorer 11

## 使い方

 ./manual.pdfをご参照ください。

## 利用OSS

本ツールでは、学習指導要領コードを検索する処理において、 　経済産業省がオープンソース（MIT LICENSE）として公開している IMI コンポーネントツールである 　「産業分類候補生成パッケージ一式」を利用しています。 　 　[参照] 　https://info.gbiz.go.jp/tools/imi_tools/index.html 　https://github.com/code4sabae/imi-enrichment-jsic-es 　 　 　
その他、以下の OSS を利用しています。

| Plugin          |                                                 | MIT License |
| --------------- | ----------------------------------------------- | ----------- |
| Express v4.18.2 | [https://github.com/expressjs/express][express] | Copyright (c) 2009-2014 TJ Holowaychuk <tj@vision-media.ca><br/> Copyright (c) 2013-2014 Roman Shtylman <shtylman+expressjs@gmail.com> Copyright (c) 2014-2015 Douglas Christopher Wilson <doug@somethingdoug.com>|
| SQLite v5.1.4   | [https://www.npmjs.com/package/sqlite3][sql]    | Copyright (c) MapBox All rights reserved. |
| Jquery v1.8.3   | [https://jquery.com/download/][jquery]          | Copyright (c) JS Foundation and other contributors | jquery.org/license            |

## License

WFC

[//]: # "These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax"
[sql]: https://www.npmjs.com/package/sqlite3
[jquery]: https://jquery.com/download/
[express]: https://github.com/expressjs/express
