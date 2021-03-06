![logo](https://avatars0.githubusercontent.com/u/24429466?s=200&u=031180a39da9253ac73d782dabb27d46cf828e37&v=4)

[![NPM version](https://img.shields.io/badge/npm-2.0.1-brightgreen.svg)](https://www.npmjs.com/package/weapp.socket.io)
[![GitHub forks](https://img.shields.io/github/forks/10cella/weapp.socket.io.svg)](https://github.com/10cella/weapp.socket.io/network)
[![GitHub stars](https://img.shields.io/github/stars/10cella/weapp.socket.io.svg)](https://github.com/10cella/weapp.socket.io/stargazers)
[![GitHub license](https://img.shields.io/github/license/10cella/weapp.socket.io.svg)](https://github.com/10cella/weapp.socket.io/blob/master/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/10cella/weapp.socket.io.svg)](https://github.com/10cella/weapp.socket.io/issues)

weapp.socket.io is a client live in Wechat mini program environment based-on [socket.io](https://socket.io/) and full features to [socket.io-client](https://github.com/socketio/socket.io-client) a browser version.

# Feature

Full feature socket.io style implemented, based-on `socket.io@2.0` version

> NOTE: Only support websocket transport, removed polling transport.

# Demos

[Weapp Demo](https://github.com/wxsocketio/socket.io-weapp-demo)

[Wepy Demo](https://github.com/weapp-socketio/wepy-demo-socket.io)

# Install

If you use a third-party framework such as [wepy](https://github.com/Tencent/wepy), you should install via `npm`

```
  npm i weapp.socket.io
```

Or if you use the native way to write code，I recommend using `git clone`

```
  git clone https://github.com/10cella/weapp.socket.io

  npm run build

  cp path/weapp.socket.io/dist/weapp.socket.io.js path/your_weapp_dir
```

# Usage

code style is same to [socket.io-client](https://github.com/socketio/socket.io-client)

```
const io = require('./yout_path/weapp.socket.io.js')

const socket = io('http://localhost:8000')

socket.on('news', d => {
  console.log('received news: ', d)
})

socket.emit('news', { title: 'this is a news' })
```

# API

See [socket.io-client API](https://github.com/socketio/socket.io-client/blob/master/docs/API.md)

# TODO

- AliPay mini program support

# Contributing

<img src="https://avatars3.githubusercontent.com/u/18544015?s=100&u=2ef4c96445ee5cc3b9b4b9817666287f85b77068&v=4" style="border-radius: 50%" />

# 用户信息征集

如果你的项目正在使用 [weapp.socket.io](https://github.com/weapp-socketio/weapp.socket.io) 欢迎留下你的项目信息（名称，Logo，官网等）

> 可以在 [这个 Issue](https://github.com/weapp-socketio/weapp.socket.io/issues/13) 提交您的项目信息
