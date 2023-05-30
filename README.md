# @cdlab996/lowcode-engine-ext-vue

<!-- [![English badge](https://img.shields.io/badge/%E8%8B%B1%E6%96%87-English-blue)](./README.md)
[![简体中文 badge](https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-Simplified%20Chinese-blue)](./README-zh_CN.md)\
English | [简体中文](./README-zh_CN.md) -->

[![NPM](https://nodei.co/npm/@cdlab996/lowcode-engine-ext-vue.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/@cdlab996/lowcode-engine-ext-vue/)

[![npm version](https://img.shields.io/npm/v/@cdlab996/lowcode-engine-ext-vue.svg)](https://www.npmjs.com/package/@cdlab996/lowcode-engine-ext-vue)
[![npm downloads](https://img.shields.io/npm/dm/@cdlab996/lowcode-engine-ext-vue.svg)](https://www.npmjs.com/package/@cdlab996/lowcode-engine-ext-vue)
[![GitHub license](https://img.shields.io/github/license/cdLab996/lowcode-engine-ext-vue)](https://github.com/cdLab996/lowcode-engine-ext-vue/blob/main/LICENSE)

## Description

- For more information, please visit the official website: [href](https://lowcode-engine.cn/site/docs/guide/appendix/setters)

- **The difference with [lowcode-engine-ext](https://github.com/alibaba/lowcode-engine-ext) is that it adapts to Vue.**

## Usage

### npm

```bash
npm install @cdlab996/lowcode-engine-ext-vue
```

### cdn

<!-- https://unpkg.com/browse/@cdlab996/lowcode-engine-ext-vue@1.0.1/ -->
<!-- https://unpkg.com/browse/@cdlab996/lowcode-engine-ext@latest/ -->

```html
https://unpkg.com/@cdlab996/lowcode-engine-ext-vue@latest/dist/css/engine-ext.css

https://unpkg.com/@cdlab996/lowcode-engine-ext-vue@latest/dist/js/engine-ext.js
```

## Local Usage

```bash
git clone https://github.com/cdLab996/lowcode-engine-ext-vue.git
cd lowcode-engine-vue
npm install
npm run start
```

- XSwitch

```json
{
  "proxy": [
    [
      "https://alifd.alicdn.com/npm/@alilc/lowcode-engine-ext@1.0.5/dist/css/engine-ext.css",
      "http://localhost:4008/js/engine-ext.css"
    ],
    [
      "https://alifd.alicdn.com/npm/@alilc/lowcode-engine-ext@1.0.5/dist/css/engine-ext.js",
      "http://localhost:4008/js/engine-ext.js"
    ]
  ]
}
```

## 🎈 License

This project is a branch of [lowcode-engine-ext](https://github.com/alibaba/lowcode-engine-ext).
