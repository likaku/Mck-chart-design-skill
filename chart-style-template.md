# 编辑型折线图 — Midjourney 提示词风格模板

> 提炼自：多系列折线图（能源消费趋势图）
> 风格参考：Financial Times / The Economist 编辑型数据可视化

---

## 设计元素速查

| 元素 | 描述 |
|------|------|
| 图表类型 | 多系列折线图 (Multi-line Time Series) |
| 背景 | 纯白，无边框 |
| 配色 | 冷色调：天蓝、深蓝、青绿、淡青、淡紫、紫色 + 黑色焦点线 |
| 线条粗细 | 焦点线加粗(~3px)，其余中粗/细线 |
| 高亮区域 | 浅灰半透明垂直带，标记关键时间窗口 |
| 标注 | 图内右上方，粗体标题 + 小字说明，无箭头 |
| 标签 | 直接标注在线条右端（Direct labeling），无图例框 |
| 坐标轴 | 极简，仅整数刻度，无网格线 |
| 字体 | Arial |
| 比例 | 16:9 宽屏横向 |
| 风格 | 极简主义 · 编辑型 · 注释驱动叙事 |

---

## Midjourney 提示词模板

### 模板 A：基础版
```
A clean minimalist multi-line chart showing 【数据主题】 over 【时间范围】. 【N】 colored lines in a cool-tone palette (cyan, dark blue, teal, lavender, purple) on a pure white background. One line highlighted in bold black as the focal point. A subtle light gray translucent vertical band highlights a key period. Direct line labels on the right side, no legend box. Annotation text in the upper right area with bold title and smaller description. Minimal axes with no gridlines. Wide aspect ratio, editorial data visualization style, Financial Times aesthetic. --ar 3:1 --style raw --v 6
```

### 模板 B：完整精细版
```
Professional editorial line chart, white background, no border. 【N】 trend lines plotted over time (X-axis: 【时间格式】, Y-axis: 【数值范围】). Color scheme: bold black focal line, cyan, dark navy blue, teal, light cyan, lavender, purple. Lines have varying thickness — the main story line is thickest in black. A semi-transparent pale gray vertical highlight band marks the key event zone spanning 【起止时间】. Inline labels at the right end of each line matching line colors, no separate legend. Top-right annotation block: bold sans-serif title "【标注标题】" with 2-line smaller description underneath. No gridlines, minimal tick marks, clean sans-serif typography (Helvetica style). Wide cinematic layout, generous whitespace, data-ink ratio maximized, Economist / FT editorial infographic style. --ar 3:1 --style raw --s 50 --v 6
```

### 模板 C：快速简洁版
```
Minimalist multi-line time series chart, 【N】 lines, cool blue-purple palette with one bold black highlight line, white background, no gridlines, direct labels in Arial font, gray highlight band, editorial annotation, Financial Times style infographic. --ar 16:9 --style raw --v 6
```

---

## 使用说明

替换 【】 中的占位符即可。需要提供：
1. 数据主题
2. 数据线数量和名称
3. 时间范围
4. 焦点数据线
5. 高亮事件描述
6. （可选）配色调整
