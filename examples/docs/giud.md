# h7ui

`h7ui` 是一款基于 `Vue.js 2.0` 的前端 UI 组件库，主要用于快速开发 PC 网站中后台产品
[演示地址](https://h7ml.github.io/h7ui/gh-page/)

## 特性

- 基于 `Vue` 开发的 UI 组件
- 使用 npm + webpack + babel 的工作流，支持 ES2015
- 提供友好的 API，可灵活的使用组件

## 浏览器支持

- 现代浏览器和 IE9 及以上
- [Electron](http://electron.atom.io/)
- [NW.js](http://nwjs.io)

## 安装

- yarn

```bash
yarn add h7ui
```

- npm 

```bash
npm install h7ui --save
```

## 使用

```js
import h7ui from 'h7ui' // 引入组件库
import 'h7ui/packages/theme-default/lib/index.css' // 引入样式库

Vue.use(h7ui)
```

## 贡献

如果你在使用 `h7ui` 时遇到问题，或者有好的建议，欢迎给我们提 [Issue](https://github.com/h7ml/h7ui/issues) 或 [Pull Request](https://github.com/h7ml/h7ui/pulls)


## Pull requests 规范

**Working on your first Pull Request?** You can learn how from this *free* series
[How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

All pull requests are welcome. Thanks for taking the time to contribute.

- Create an issue about the features, such as new components.
- Fork the repo to your own account.
- Clone your fork.
- Create a new branch base on `dev`, if you want to add new component, the branch name should be formatted as `component-[Component Name]`. (e.g. `component-steps`) And the commit info should be formatted as `[Component Name]: Info about commit`.
- Make sure that running `npm run prepublish` outputs the correct files.
- Rebase before creating a PR to keep commit history clear. (Merge request to branch `dev`)
- Provide some description about your PR.
