# 前端小项目合集

从零用原生 HTML / CSS / JavaScript 实现的前端小项目，零依赖、零构建，每个 demo 双击 `index.html` 即可运行。

## 在线预览

开启 GitHub Pages 后访问：`https://lx88886.github.io/<仓库名>/`

## 项目列表

| # | 项目 | 知识点 |
|---|------|--------|
| 01 | [展开式卡片](./demos/expanding-cards/index.html) | Flex 弹性布局、CSS transition、class 切换 |
| 02 | [分屏着陆页](./demos/split-landing/index.html) | CSS 变量、:hover、absolute 定位、移动端适配 |
| 03 | [滚动数字看板](./demos/counter/index.html) | IntersectionObserver、requestAnimationFrame、缓动函数 |

## 怎么跑

直接用浏览器打开根目录 `index.html`；或在本目录起个静态服务：

```bash
python -m http.server 8080
# 访问 http://localhost:8080
```

## 说明

- 所有效果均不依赖任何第三方库或外部图片资源（渐变配色代替图片），离线可用
- 练习思路参考 [50projects50days](https://github.com/bradtraversy/50projects50days)（MIT），代码为自行实现并改写
