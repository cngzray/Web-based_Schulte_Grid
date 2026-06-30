# 舒尔特方格专注力训练工具
零依赖、开箱即用，支持计时自动随机生成5×5数字方格

[![Static Badge](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Static Badge](https://img.shields.io/badge/HTML-CSS-JS-orange)]()
[![Static Badge](https://img.shields.io/badge/无第三方依赖-green)]()

## 项目简介
舒尔特方格是经典视觉专注力训练工具，本项目使用原生 HTML/CSS/JavaScript 实现，不引入任何框架、第三方库，单文件 `index.html` 即可完整运行。
随机生成 1~25 无序数字 5×5 方格，内置高精度计时器，自动记录完成训练耗时，附带官方专注力评分标准，适合学生、成人日常注意力训练、专注力自测。

直接试玩： https://cngzray.github.io/Web-based_Schulte_Grid/

<img width="600" height="643" alt="image" src="https://github.com/user-attachments/assets/7832c388-e3ed-435e-822f-a2b899f02a0d" />

## 核心功能
1. **一键随机生成方格**：点击「开始」自动洗牌重排1-25数字，每个数字独立彩色字体，区分度更高
2. **高精度计时**：基于 `requestAnimationFrame` 毫秒级计时，显示保留1位小数
3. **简洁交互**：开始/停止双状态按钮，启动刷新方格、停止锁定计时
4. **轻量化无依赖**：仅单个HTML文件，浏览器直接打开运行，无需服务器、打包工具
5. **友好UI**：hover缩放动效、圆角卡片、柔和背景，长时间训练视觉舒适
6. **内置评分标准**：页面底部自带专注力等级判定，训练完成直接对照成绩

## 训练评分标准
项目内置官方评判标准，按1~25完整查找用时划分：
- ✨ 优秀：35 秒以内
- 👍 良好：35～45 秒
- ✅ 合格：45～60 秒
- ⚠️ 偏弱：60 秒以上

用时越短，代表视觉专注力、视觉追踪、反应速度、抗干扰能力越强。

## 自定义修改指南
你可以简单修改代码自定义训练效果：
1. **调整方格尺寸**：修改 `.matrix` 内 `grid-template-columns / grid-template-rows` 的 `80px` 数值
2. **修改单元格大小、字体**：调整 `.cell` 内 `font-size`、宽高
3. **更换配色**：修改 `colorList` 数组内十六进制色值
4. **调整标题/计时器字号**：修改 h2、.timer 内 font-size
5. **拓展方格规格**：可扩展为4×4/6×6，同步修改数组长度与网格行列

## 适用人群
- 中小学生：提升上课专注度、改善做题粗心、训练视觉追踪
- 成人/职场：缓解注意力涣散、提升阅读速读、工作专注力训练
- 速读、记忆力爱好者：日常基础专注力训练工具
