# 示例：中国主要粮油产品价格波动 — Midjourney 提示词

## 一、数据背景梳理（2020–2025）

### 主要粮食品种价格走势概况

| 品种 | 2020 | 2021 | 2022 (高峰) | 2023 | 2024 | 走势特征 |
|------|------|------|-------------|------|------|----------|
| 小麦 | ~2400元/吨 | ~2600元/吨 | **~3200元/吨** | ~2900元/吨 | ~2350元/吨 | 冲高回落，2022年见顶 |
| 玉米 | ~2100元/吨 | ~2700元/吨 | **~3000元/吨** | ~2600元/吨 | ~2200元/吨 | 与小麦类似，先涨后跌 |
| 稻谷 | ~2600元/吨 | ~2700元/吨 | ~2800元/吨 | ~2800元/吨 | ~2825元/吨 | 相对平稳，缓慢上行 |
| 大豆 | ~4500元/吨 | ~5500元/吨 | **~5800元/吨** | ~5200元/吨 | ~4900元/吨 | 受国际市场影响大 |

### 主要食用油价格走势概况

| 品种 | 2020 | 2021 | 2022 (高峰) | 2023 | 2024 | 走势特征 |
|------|------|------|-------------|------|------|----------|
| 豆油 | ~6500元/吨 | ~9500元/吨 | **~10500元/吨** | ~8000元/吨 | ~7800元/吨 | 暴涨暴跌，波动最大 |
| 菜籽油 | ~8000元/吨 | ~11000元/吨 | **~13000元/吨** | ~9500元/吨 | ~8800元/吨 | 跟随豆油但价位更高 |
| 花生油 | ~15000元/吨 | ~17000元/吨 | **~18000元/吨** | ~16500元/吨 | ~14600元/吨 | 高位运行后持续回落 |

### 关键事件节点
- **2020年**：新冠疫情初期恐慌性囤粮，价格温和上涨
- **2021年**：全球通胀+供应链紧张，粮油价格大幅攀升
- **2022年2月**：**俄乌冲突爆发** → 全球粮价飙升，中国粮油价格达到近年高峰（⬆️ 焦点事件）
- **2023年**：全球供应恢复，国内粮价持续回调
- **2024年**：国内丰产+进口增量，小麦玉米跌至近3年低位

---

## 二、图表设计规划

### 数据线设计（7条线）

| 线条 | 对应品种 | 颜色 | 线条粗细 | 说明 |
|------|----------|------|----------|------|
| **焦点线** | 豆油 (Soybean Oil) | **黑色 (Bold Black)** | 加粗 ~3px | 波动最剧烈，作为叙事主线 |
| 线2 | 菜籽油 (Rapeseed Oil) | 深蓝色 (Dark Navy) | 中粗 | 紧跟豆油走势 |
| 线3 | 花生油 (Peanut Oil) | 天蓝色 (Cyan) | 中粗 | 高价位段 |
| 线4 | 大豆 (Soybean) | 青绿色 (Teal) | 中粗 | 原料端 |
| 线5 | 小麦 (Wheat) | 淡青色 (Light Cyan) | 细线 | 主粮代表 |
| 线6 | 玉米 (Corn) | 淡紫色 (Lavender) | 细线 | 饲料粮代表 |
| 线7 | 稻谷 (Rice) | 紫色 (Purple) | 细线 | 最平稳的品种 |

### 高亮区域
- **2022年Q1-Q2**（俄乌冲突爆发期）→ 浅灰色半透明垂直带

### 注释标注
- **标题**："Oil price surge"
- **说明**："In early 2022, the Russia-Ukraine conflict triggered a sharp rally in global edible oil prices"

---

## 三、Midjourney 提示词

### ✅ 推荐版（精细版）

```
Professional editorial line chart showing China's major grain and edible oil price trends from 2020 to 2025, white background, no border. 7 trend lines plotted over time (X-axis: years 2020 to 2025 with quarterly intervals, Y-axis: price in CNY/ton ranging from 2000 to 18000). Color scheme: bold black focal line representing soybean oil prices with the most dramatic fluctuation, dark navy blue line for rapeseed oil, cyan line for peanut oil at the highest price range, teal line for soybean, light cyan for wheat, lavender for corn, and purple for rice at the most stable trajectory. Lines have varying thickness — soybean oil is thickest in bold black as the main story. All lines show a clear rise from 2020, peaking around early 2022, then gradually declining through 2023-2024. A semi-transparent pale gray vertical highlight band marks the key event zone spanning Q1 to Q2 2022 when the Russia-Ukraine conflict caused prices to spike. Inline labels at the right end of each line in matching colors: "Peanut Oil", "Rapeseed Oil", "Soybean Oil", "Soybean", "Wheat", "Corn", "Rice", no separate legend box. Top-right annotation block: bold Arial title "Oil price surge" with 2-line smaller description "In early 2022, the Russia-Ukraine conflict triggered a sharp rally in global edible oil prices". No gridlines, minimal tick marks, clean Arial typography throughout. Wide cinematic layout, generous whitespace, data-ink ratio maximized, Economist / Financial Times editorial infographic style. --ar 16:9 --style raw --s 50 --v 6
```

### ✅ 基础版

```
A clean minimalist multi-line chart showing China's grain and edible oil price fluctuations from 2020 to 2025. 7 colored lines in a cool-tone palette (cyan, dark blue, teal, lavender, purple) on a pure white background. One bold black line representing soybean oil as the focal point with the most dramatic rise and fall. All lines peak around early 2022 and gradually decline. A subtle light gray translucent vertical band highlights the Q1-Q2 2022 period when Russia-Ukraine conflict impacted prices. Direct line labels on the right side reading "Peanut Oil", "Rapeseed Oil", "Soybean Oil", "Soybean", "Wheat", "Corn", "Rice", no legend box. Annotation text in the upper right: bold title "Oil price surge" with smaller description about the 2022 conflict impact. Minimal axes with no gridlines, Y-axis showing price in CNY/ton. All text in Arial font. Editorial data visualization style, Financial Times aesthetic. --ar 16:9 --style raw --v 6
```

### ✅ 简洁版

```
Minimalist multi-line time series chart, 7 lines showing China grain and oil prices 2020-2025, cool blue-purple palette with one bold black highlight line for soybean oil peaking in 2022, white background, no gridlines, direct labels in Arial font (Peanut Oil, Rapeseed Oil, Soybean Oil, Soybean, Wheat, Corn, Rice), gray highlight band marking Russia-Ukraine conflict period Q1 2022, editorial annotation "Oil price surge", Financial Times style infographic. --ar 16:9 --style raw --v 6
```

### ✅ 中文版

```
专业编辑型折线图，展示中国主要粮油产品2020-2025年价格波动趋势。纯白背景，无边框。7条趋势线：豆油（黑色加粗焦点线，波动最大）、菜籽油（深蓝色）、花生油（天蓝色，最高价位）、大豆（青绿色）、小麦（淡青色）、玉米（淡紫色）、稻谷（紫色，最平稳）。所有线条在2022年初达到峰值后逐步回落。2022年Q1-Q2区间有浅灰色半透明高亮带标注俄乌冲突时期。线条右端直接标注品种名称，无图例框。右上角注释：粗体标题"油价飙升"，小字说明"2022年初俄乌冲突引发全球食用油价格急涨"。无网格线，极简坐标轴，所有文字使用Arial字体，16:9宽屏横向布局，经济学人/金融时报风格。--ar 16:9 --style raw --v 6
```

---

## 四、使用建议

1. **推荐首选精细版**：信息最完整，Midjourney 能更好理解你的意图
2. **如果生成效果不理想**：可尝试简洁版，减少干扰信息
3. **参数调整**：
   - `--s 50`：风格化程度适中（减小可更写实）
   - `--v 6`：使用 V6 模型（文字渲染能力更强）
   - `--style raw`：减少 Midjourney 自带的美化倾向，更贴近真实图表
4. **注意**：Midjourney 对精确数值的控制有限，生成的图表更偏"视觉示意"而非精确数据图
