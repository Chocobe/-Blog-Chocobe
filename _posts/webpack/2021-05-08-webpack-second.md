---
layout: post
current: post
cover: assets/images/tagImage/bg_webpack.png
hideCover: True
navigation: True
title: #02> Webpack 개발환경 만들기
date: 2021-05-08 15:31:00
tags: [webpack]
class: post-template
subclass: 'post'
author: chocobe
---

{% include content-list-webpack.html %}

## #02> Webpack 개발환경 만들기

세번째 포스팅 입니다.

> 예제코드

<br/>

```javascript
const path = require("path");

module.exports = {
  mode: "none",
  entry: "app.js",
  output: {
    filename: "app.bundle.js",
    path: path.resolve(__dirname, "dist")
  },
  
  exclude: ["node_modules", "dist"]
};
```

<br/>

감사합니다 🐫