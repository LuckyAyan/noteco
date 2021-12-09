<h1 align="center">Noteco</h1>

<p align="center">
    <a href="https://www.npmjs.org/package/noteco">
        <img src="https://img.shields.io/npm/v/noteco.svg">
    </a>
    <a href="https://npmcharts.com/compare/noteco?minimal=true">
        <img src="http://img.shields.io/npm/dm/noteco.svg">
    </a>
  <br>
</p>

<p align="center">
    Noteco，是一款由 dumi 构建，基于 React + TypeScript 的组件库 🚀
</p>

<p align="center">
    文档：https://RyanProMax.github.io/noteco/
</p>

## 🌼 Just component, not UI.

没有 UI 设计，只专注逻辑本身。

### ❓ what is this

这是一个用于学习的组件库，注释说明每一个组件的实现思路。

## 📦 安装

### 使用 npm 或 yarn 安装

```bash
npm install noteco
```

```bash
yarn add noteco
```

## 🔨 使用

### 按需加载

`noteco` 默认支持按需加载，直接通过 ES Modules 引入即可，充分利用 Tree Shaking 机制。

### 示例

```js
import { FPS } from 'noteco';

const Component = () => <FPS />;
```

## 📅 计划

### UI 组件

- [x] Avatar - 选择头像
- [x] Divider - 分割线
- [x] Input - 输入框
- [x] Pagination - 分页器

### 功能组件

- [x] FPS - 帧率检测
- [x] Watermark - 水印
- [x] DragList - 拖拽列表
- [x] VirtualList - 虚拟列表
- [ ] Transition - 过渡动画组件

### 动画组件

这部分内容的实现主要参照大佬的作品：https://csscoco.com/inspiration/ ，加以封装方便复用。

- [x] AnimateLineSimpleText - 线性动画文字
- [x] AnimateLineText - 线性动画文字
- [x] BreakText - 故障文字
- [x] NumberCount3D - 3D 数字
- [x] OutlineAnimation - 线条动画
- [x] StringRain - 字符雨
