# 小提琴音符英雄

一个面向儿童识谱练习的小提琴小游戏静态站点。

在线访问：
[https://jnwang.github.io/violin-note-hero/](https://jnwang.github.io/violin-note-hero/)

当前默认首页：
`violin3.html`

## 文件说明

- `index.html`：站点入口，默认跳转到 `violin2.html`
- `violin.html`：第一版页面
- `violin2.html`：第二版页面
- `violin3.html`：当前默认展示版本
- `styles.css`：本地打包后的样式文件
- `input.css`：Tailwind 样式入口

## 本地更新样式

安装依赖：

```bash
npm install
```

重新生成样式：

```bash
./node_modules/.bin/tailwindcss -i ./input.css -o ./styles.css --minify
```

## 发布方式

本项目通过 GitHub Pages 发布，仓库地址：
[https://github.com/jnwang/violin-note-hero](https://github.com/jnwang/violin-note-hero)

提交并推送到 `main` 分支后，GitHub Pages 会自动更新。

## 说明

为了提升中国访问稳定性，页面已去掉 Google Fonts 和 Tailwind CDN 外链，改为本地静态资源。
