<p align="center">
  <img src="assets/logo-placeholder.png" alt="Chart Prompt Generator" width="120">
</p>

<h1 align="center">📊 Chart Prompt Generator</h1>

<p align="center">
  <strong>专业编辑型图表风格 · AI 提示词生成器</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-🚧_Alpha_预览版-orange?style=flat-square" alt="Alpha">
  <img src="https://img.shields.io/badge/version-v0.1--alpha-lightgrey?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/chart_type-折线图-blue?style=flat-square" alt="Line Chart">
</p>

<p align="center">
  一键生成专业编辑型数据可视化图表的 Midjourney 提示词<br/>
  让每个打工人都能做出专业水准的图表
</p>

<p align="center">
  <a href="#-展示画廊">展示画廊</a> •
  <a href="#-加入社群">加入社群</a> •
  <a href="#-路线图">路线图</a>
</p>

---

> **⚠️ 注意：本项目目前处于 Alpha 早期预览阶段**
>
> 当前版本仅支持**折线图**一种图表类型，功能和模板还在持续迭代中。
> 欢迎 Star 关注进展、加入社群参与讨论，但**暂不建议用于正式生产环境**。
> 更多图表类型正在路上 👇 [路线图](#-路线图)

---

## 🎯 这是什么？

**你是不是也受够了这些？**

- 🤦 汇报的图表被领导吐槽"太丑了"
- 😩 花 3 小时调 Excel 图表配色，结果还是像 Windows 95
- 😵 看到专业报告里的图表，只能感叹"别人家的图"
- 🫠 想学数据可视化，但设计规范一大堆，根本记不住

**Chart Prompt Generator 就是来解决这个问题的。**

我们把专业编辑型数据可视化的图表设计规范（参考顶级财经媒体和咨询公司的风格），提炼成了一套 **AI 提示词模板系统**。你只需要告诉 AI 你的数据主题，它就能自动生成符合专业标准的 Midjourney 图表提示词。

> 🐂🐴 打工人的图表救星 — 从此告别丑图，汇报再也不怕。

---

## ✨ 核心特性

| 特性 | 说明 |
|------|------|
| 🎨 **专业设计系统** | 参考顶级财经媒体编辑型数据可视化规范，不是随便配的色 |
| 🧊 **冷色调色板** | 7 级蓝-青-紫渐变 + 黑色焦点线，拿来就能用 |
| 📐 **标准化布局** | 16:9 宽屏、直接标签、无网格线、注释驱动叙事 |
| 🤖 **4 版提示词** | 精细版 / 基础版 / 简洁版 / 中文版，适配不同场景 |
| 📊 **AI 辅助工作流** | 自动搜索数据趋势 → 规划设计 → 生成提示词，全流程 SOP |
| 🔤 **统一字体** | Arial 字体，全球通用，不挑系统 |

---

## 🚀 使用方式（开发中）

> 🚧 **本项目仍在早期开发阶段，以下功能尚未完全开放。**
> 欢迎 Star 关注，我们会在功能稳定后发布正式版本。

### 计划中的使用方式

**方式一：AI Skill（规划中）**

作为 AI 编程助手的 Skill 插件，直接对话即可生成图表提示词。

**方式二：模板文件**

参考 [`chart-style-template.md`](chart-style-template.md) 中的提示词模板，手动替换占位符后粘贴到 Midjourney。

**方式三：示例参考**

查看 [`examples/`](examples/) 目录中的完整示例，了解提示词的写法和效果。

---

## 🎨 设计系统一览

### 配色方案

```
■ #000000  焦点线（黑色加粗）  ━━━━━ 主角，波动最大的数据
■ #003399  深蓝色              ━━━━  紧随主角的数据
■ #00BFFF  天蓝色              ━━━━  高位数据
■ #008080  青绿色              ━━━━  中位数据
■ #66CCCC  淡青色              ───── 配角数据
■ #9999CC  淡紫色              ───── 配角数据
■ #660099  紫色                ───── 最平稳的数据
```

### 布局结构

```
┌──────────────────────────────────────────────────────────────────────┐
│                              [注释标题 + 说明文字]（右上偏中）         │
│  Y轴 ─                                                               │
│        ═══════ 焦点线(黑色加粗) ══════════════════  Label1            │
│        ═══════ 系列线 ═════════╗ ┌──灰色高亮带──┐ ═══ Label2         │
│        ═══════ 系列线 ═════════╝ │              │ ═══ Label3         │
│        ═══════ 系列线 ══════════ │              │ ═══ Label4-N       │
│  0 ──────────────────────────────└──────────────┘────────────         │
│       时间1    时间2    时间3    时间4    时间5    时间6               │
└──────────────────────────────────────────────────────────────────────┘
```

### 核心设计原则

- **极简主义** — 去除一切非必要元素，最大化 Data-Ink Ratio
- **注释驱动叙事** — 用标注讲故事，不让读者自己猜
- **直接标签** — 标签贴着数据走，扔掉图例框
- **焦点突出** — 一条黑色粗线当主角，其余甘当绿叶
- **留白美学** — 大量留白，让图表呼吸

---

## 🖼️ 展示画廊

> 💡 以下展示了使用本项目提示词生成的图表效果。左侧为提示词摘要，右侧为 Midjourney 生成结果。

### 示例 1：中国粮油价格波动趋势（2020-2025）

**提示词摘要：**
> Professional editorial line chart showing China's major grain and edible oil price trends from 2020 to 2025, 7 trend lines, bold black focal line for soybean oil, cool-tone palette, gray highlight band marking Russia-Ukraine conflict...

<p align="center">
  <img src="assets/gallery/example-01-grain-oil.png" alt="中国粮油价格波动" width="800">
  <br/>
  <em>7 条数据线 · 豆油为焦点线 · 2022 俄乌冲突高亮区</em>
</p>

---

### 示例 2：待添加

**提示词摘要：**
> *Coming soon...*

<p align="center">
  <img src="assets/gallery/example-02-placeholder.png" alt="示例 2" width="800">
  <br/>
  <em>即将添加</em>
</p>

---

### 示例 3：待添加

**提示词摘要：**
> *Coming soon...*

<p align="center">
  <img src="assets/gallery/example-03-placeholder.png" alt="示例 3" width="800">
  <br/>
  <em>即将添加</em>
</p>

---

### 示例 4：待添加

**提示词摘要：**
> *Coming soon...*

<p align="center">
  <img src="assets/gallery/example-04-placeholder.png" alt="示例 4" width="800">
  <br/>
  <em>即将添加</em>
</p>

---

## 📁 项目结构

```
chart-prompt-generator/
├── README.md                          # 你在看的这个文件
├── chart-style-template.md            # 通用图表风格模板（3 版提示词）
├── examples/
│   └── china-grain-oil-price.md       # 示例：中国粮油价格波动
├── assets/
│   ├── gallery/                       # 展示画廊图片
│   │   ├── example-01-grain-oil.png   # 示例 1 效果图
│   │   └── ...
│   ├── wechat-group-qr.png            # 微信群二维码
│   └── logo-placeholder.png           # 项目 Logo
└── .gitignore
```

---

## 🗺️ 路线图

当前版本 (v0.1-alpha) 仅包含 **折线图 (Line Chart)** 一种图表类型，更多格式正在开发中：

- [x] 📈 **折线图 (Line Chart)** — 趋势分析、时间序列 ← *当前版本 (alpha)*
- [ ] 📊 **柱状图 (Bar Chart)** — 对比分析、排名展示
- [ ] 🍩 **环形图 / 饼图 (Donut / Pie Chart)** — 占比分析
- [ ] 📉 **面积图 (Area Chart)** — 堆叠趋势、份额变化
- [ ] 🔵 **散点图 (Scatter Plot)** — 相关性分析
- [ ] 🗺️ **地图热力图 (Heatmap / Choropleth)** — 地理分布
- [ ] 📋 **瀑布图 (Waterfall Chart)** — 财务增减分析
- [ ] 🌊 **桑基图 (Sankey Diagram)** — 流向分析
- [ ] 📐 **甘特图 (Gantt Chart)** — 项目时间线

> 💬 有想要的图表类型？欢迎在 [Issues](../../issues) 中提出，或加入社群讨论！

---

## 💬 加入社群

我们正在建设一个围绕 **AI + 数据可视化** 的社群，欢迎所有对 AI 图表生成感兴趣的朋友加入！

<table>
  <tr>
    <td align="center" width="300">
      <h3>📱 微信群</h3>
      <img src="assets/wechat-group-qr.png" alt="微信群二维码" width="200">
      <br/><br/>
      <em>扫码加入微信交流群</em>
      <br/>
      <sub>（二维码过期请提 Issue 联系）</sub>
    </td>
    <td align="center" width="300">
      <h3>💬 Discord</h3>
      <br/><br/>
      <a href="https://discord.gg/YOUR_INVITE_LINK">
        <img src="https://img.shields.io/badge/Discord-加入社群-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
      </a>
      <br/><br/>
      <em>点击加入 Discord 服务器</em>
      <br/>
      <sub>国际交流、英文频道</sub>
    </td>
  </tr>
</table>

---

## 🤝 贡献

欢迎贡献！你可以：

1. 🐛 **提 Issue** — 反馈问题或建议新图表类型
2. 🎨 **提交展示** — 用本项目生成了好看的图表？欢迎 PR 到展示画廊
3. 📝 **完善模板** — 优化提示词模板或新增图表类型
4. 🌍 **翻译** — 帮助翻译成其他语言

---

## 📄 License

[MIT](LICENSE) © 2026

---

<p align="center">
  <strong>⭐ 如果这个项目有潜力，请给个 Star 关注后续进展！</strong>
</p>

<p align="center">
  <sub>🚧 Alpha 阶段 · 持续开发中 · 让每个打工人的汇报图表都能专业起来</sub>
</p>
