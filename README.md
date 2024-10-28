<p align="center">
<svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>Vue.js</title><path d="M24,1.61H14.06L12,5.16,9.94,1.61H0L12,22.39ZM12,14.08,5.16,2.23H9.59L12,6.41l2.41-4.18h4.43Z"/></svg>
</div>
</p>
<h1 align="center">SSY-UI-VITE</h1>
<p align="center">
  基于 Vite 栈的前端工程化实践
</p>
<p align="center">
<img src="https://img.shields.io/github/license/Nagnahs-1/Web-SSY-UI-VITE?color=red">
</p>

## Features
- 基于 Vue 框架
-支持 JSX与 Vue 单文件组件
-Jest + Vue3 plugins实现单元测试
-Eslint + Prettier + Husky 语法检查
-采用 Rollup 构建
-Vitepress + Vercel 文档网站搭建
-基于Action CI 实现持续集成与交付
## Install

```bash
npm i ssy-ui-vite
```

## Quick Start

```vue
import Vue from 'vue'
import SSYUI from 'ssy-ui-vite'
const App = { template: `
<SButton  color="blue">
主要按钮
</SButton>
`, };
createApp(App)
.use(SSYUI)
.mount("#app");
```

## Browser Support

支持大多数现代浏览器和 IE10+

# Join Us

如果希望尽快上手，可以访问[Getting Started](https://web-ssy-ui-vite.vercel.app/)
