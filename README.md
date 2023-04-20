# @cdlab996/lowcode-engine-ext-vue

[![NPM](https://nodei.co/npm/@cdlab996/lowcode-engine-ext-vue.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/@cdlab996/lowcode-engine-ext-vue/)

[![npm version](https://img.shields.io/npm/v/@cdlab996/lowcode-engine-ext.svg)](https://www.npmjs.com/package/@cdlab996/lowcode-engine-ext-vue)
[![npm downloads](https://img.shields.io/npm/dm/@cdlab996/lowcode-engine-ext.svg)](https://www.npmjs.com/package/@cdlab996/lowcode-engine-ext-vue)
[![GitHub license](https://img.shields.io/github/license/@cdlab996/lowcode-engine-ext-vue)](https://github.com/cdlab996/lowcode-engine-ext-vue/blob/main/LICENSE)

## Synopsis

- 更多请查看官网: [href](https://lowcode-engine.cn/site/docs/guide/appendix/setters)

- **与 [lowcode-engine-ext](https://github.com/alibaba/lowcode-engine-ext) 不同点在于，对 Vue 进行适配**

<!-- See more at [Official setter](https://lowcode-engine.cn/site/docs/guide/appendix/setters) -->

<!-- **The difference with [lowcode-engine-ext](https://github.com/alibaba/lowcode-engine-ext) is that the adaptation to Vue.** -->

## use

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

## Local

``` bash
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

This is a fork from [lowcode-engine-ext](https://github.com/alibaba/lowcode-engine-ext)
