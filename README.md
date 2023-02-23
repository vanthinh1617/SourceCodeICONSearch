# ICON Search

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## Installation

Requires [Node.js](https://nodejs.org/) v16.13.1 to run.

Install the dependencies and devDependencies and start the server.

Test on window, install lib

```sh
npm install -g win-node-env
```

Run on Development enviroment

```sh
cd icon-search
npm i
npm run watch:dev
```

Run on Production enviroment

```sh
npm run start
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin  | README                                |
| ------- | ------------------------------------- |
| Express | [plugins/express/README.md][express]  |
| SQLite  | [plugins/sqlite/README.md][sql]       |
| GitRepo | [plugins/git/README.md][git-repo-url] |

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:3000
```

## License

WFC

**Free Software, Hell Yeah!**

[//]: # "These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax"
[sql]: https://www.sqlitetutorial.net/sqlite-nodejs/
[git-repo-url]: https://github.com/joemccann/dillinger.git
[express]: http://expressjs.com
