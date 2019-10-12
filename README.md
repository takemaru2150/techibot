# techibot
LINEBOTの開発を行いました。

 ## 仕様
- 名称：「てちbot」
- 使用言語・ツール：node.js、HEROKU、git、LINE Developers
- 開発環境：Windows10

## 機能
- 友達追加時にメッセージ「友だち追加ありがとうございます」「(username)さん！よろしくね！！」
- 自動返信

ボットサーバとして使うサーバ環境はherokuインスタンスを利用しています。
[公式ドキュメント](https://devcenter.heroku.com/articles/getting-started-with-nodejs)を参考にnode.jsアプリをherokuにデプロイし、サーバ環境の準備をしました。
以下はその際のREADMEです。

# node-js-getting-started

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
