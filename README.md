<p align="center"><a href="http://mpvue.com" target="_blank" rel="noopener noreferrer"><img width="100" src="http://mpvue.com/assets/logo.png" alt="mpvue logo"></a></p>
<p align="center">
   <a href="https://www.npmjs.com/package/mpvue"><img src="https://img.shields.io/npm/v/mpvue.svg?style=flat" alt="npm"></a>
   <a href="https://www.npmjs.com/package/mpvue"><img src="https://img.shields.io/npm/dm/mpvue.svg?style=flat" alt="npm"></a>
 </p>

# mpvue 
> Vue.js 小程序版, fork 自 [vuejs/vue@2.4.1](https://github.com/vuejs/vue)，保留了 vue runtime 能力，添加了小程序平台的支持。


`mpvue` 是一个使用 [Vue.js](https://vuejs.org) 开发小程序的前端框架。框架基于 `Vue.js` 核心，`mpvue` 修改了 `Vue.js` 的 runtime 和 compiler 实现，使其可以运行在小程序环境中，从而为小程序开发引入了整套 `Vue.js` 开发体验。

## 文档

[mpvue 文档](http://mpvue.com)

## 实践案例

美团旗下小程序：`美团火车票12306抢票`、`美团汽车票` 和 `美团充电`，此外，正有一大批小程序正在接入中。

## 快速开始

我们精心准备了一个简单的 [五分钟上手教程](http://mpvue.com/mpvue/quickstart) 方便你快速体验到 `mpvue` 带来的开发乐趣。

## 名称由来
- `mp`：mini program 的缩写
- `mpvue`：Vue.js in mini program

## 主要特性
使用 `mpvue` 开发小程序，你将在小程序技术体系的基础上获取到这样一些能力：

- 彻底的组件化开发能力：提高代码复用性
- 完整的 `Vue.js` 开发体验
- 方便的 `Vuex` 数据管理方案：方便构建复杂应用
- 快捷的 `webpack` 构建机制：自定义构建策略、开发阶段 hotReload
- 支持使用 npm 外部依赖
- 使用 `Vue.js` 命令行工具 vue-cli 快速初始化项目
- H5 代码转换编译成小程序目标代码的能力

其它特性正在等着你去探索。

### H5 和小程序如何复用代码
[先来看一段视频](http://mpvue.com/assets/20170810-022809-HD.mp4)
<video src="http://mpvue.com/assets/20170810-022809-HD.mp4" width="863" height="480" controls="controls"></video>

在左侧为已经上线的 H5 页面，右侧为同代码的小程序页面，其中只需要更改小部分平台差异代码和更新下 webpack 的建构配置就可以直接运行。

在未来最理想的状态是，可以一套代码可以直接跑在多端：WEB、小程序（微信和支付宝）、Native（借助weex）。

当然从产品的层面，我们不建议这么做，各个端有自己的差异性，我们期望的只是开发和调试体验一致。

## 配套设施
`mpvue` 作为小程序版本的 `Vue.js`，在框架 SDK 之外，完整的技术体系还包括如下设施。

- [mpvue-loader](http://mpvue.com/build/mpvue-loader) 提供 webpack 版本的加载器
- [mpvue-webpack-target](http://mpvue.com/build/mpvue-webpack-target) webpack 构建目标
- [postcss-mpvue-wxss](http://mpvue.com/build/postcss-mpvue-wxss) 样式代码转换预处理工具
- [px2rpx-loader](http://mpvue.com/build/px2rpx-loader) 样式转化插件
- [mpvue-quickstart](http://mpvue.com/mpvue/quickstart) mpvue-quickstart
- [mpvue-simple](http://mpvue.com/mpvue/simple) 辅助 mpvue 快速开发 Page / Component 级小程序页面的工具
- 其它

[贡献方法](./.github/CONTRIBUTING.md)

[使用 mpvue 的项目征集](https://github.com/Meituan-Dianping/mpvue/issues/21)

[分享交流群](https://github.com/Meituan-Dianping/mpvue/issues/14)
