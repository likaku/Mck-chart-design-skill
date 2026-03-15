# 示例：中国头部互联网公司市值波动（2020–2025）— Midjourney 提示词

## 一、数据背景梳理

### 选取公司

选取 6 家最具代表性的中国头部互联网上市公司，覆盖社交、电商、本地生活、搜索等核心赛道：

| 公司 | 代码 | 核心业务 | 市值量级 |
|------|------|----------|----------|
| 腾讯 (Tencent) | 0700.HK | 社交/游戏/金融科技 | 第一梯队 |
| 阿里巴巴 (Alibaba) | 9988.HK / BABA | 电商/云计算 | 第二梯队 |
| 拼多多 (PDD) | PDD.US | 电商/Temu 出海 | 第三梯队 |
| 美团 (Meituan) | 3690.HK | 本地生活/外卖 | 第四梯队 |
| 京东 (JD.com) | 9618.HK / JD | 电商/物流 | 第五梯队 |
| 百度 (Baidu) | 9888.HK / BIDU | 搜索/AI/自动驾驶 | 第六梯队 |

### 各公司市值走势概况（美元，近似值）

| 公司 | 2020 年初 | 2021 年高峰 | 2022 年低谷 | 2023 年末 | 2024 年末 | 2025Q1 | 走势特征 |
|------|-----------|-------------|-------------|-----------|-----------|--------|----------|
| 腾讯 | ~4900亿 | **~9500亿** | ~3300亿 | ~3500亿 | ~4950亿 | ~5100亿 | 过山车式，但恢复力最强 |
| 阿里巴巴 | ~6100亿 | **~8100亿** | ~1900亿 | ~1900亿 | ~2020亿 | ~3400亿 | 从巅峰跌去 75%，恢复最慢 |
| 拼多多 | ~450亿 | ~2000亿 | ~440亿 | **~1940亿** | ~1350亿 | ~1580亿 | 先崩后涨再回调，最戏剧性 |
| 美团 | ~800亿 | **~2600亿** | ~600亿 | ~700亿 | ~1210亿 | ~1300亿 | 暴涨暴跌后缓慢恢复 |
| 京东 | ~550亿 | **~1500亿** | ~380亿 | ~400亿 | ~590亿 | ~640亿 | 大起大落后回归平淡 |
| 百度 | ~400亿 | **~1000亿** | ~290亿 | ~350亿 | ~310亿 | ~380亿 | AI 概念短暂提振后持续低迷 |

### 关键事件节点

- **2020 年**：疫情加速数字化，互联网公司全面受益，市值普涨
- **2021 年初（峰值）**：全球流动性泛滥 + 科技股狂热，中国互联网公司市值达到历史巅峰
- **2021 年 Q2-Q4（⬇️ 监管风暴）**：
  - 蚂蚁集团 IPO 被叫停（2020.11）→ 阿里系率先下跌
  - 反垄断罚款（阿里 182 亿罚单，2021.04）
  - "双减"政策重创教育科技股（2021.07）
  - 数据安全审查（滴滴事件，2021.07）
  - 游戏版号收紧 → 腾讯承压
- **2022 年（⬇️ 至谷底）**：
  - 中概股退市风险（SEC 预退市名单）
  - 俄乌冲突 + 全球加息 → 风险资产抛售
  - 中国互联网公司市值从峰值合计蒸发超过 **2 万亿美元**
- **2023 年**：监管政策逐步明朗，拼多多凭 Temu 异军突起
- **2024 年**：分化加剧，腾讯稳步恢复，阿里持续低迷，小米成最大黑马（+122%）
- **2025 年 Q1（⬆️ DeepSeek 引领反弹）**：
  - DeepSeek R1 发布，中国 AI 能力获全球认可
  - 恒生科技指数触及近三年高点
  - 科技八巨头贡献了指数涨幅的 70%
  - 阿里巴巴年初至今涨幅超 68%

---

## 二、图表设计规划

### 数据线设计（6 条线）

| 线条 | 对应公司 | 颜色 | 线条粗细 | 选择理由 |
|------|----------|------|----------|----------|
| **焦点线** | 阿里巴巴 (Alibaba) | **黑色 (Bold Black)** | 加粗 ~3px | 跌幅最惨烈，从全球前十跌出，叙事张力最强 |
| 线 2 | 腾讯 (Tencent) | 深蓝色 (Dark Navy) #003399 | 中粗 ~2px | 第一梯队龙头，恢复力标杆 |
| 线 3 | 拼多多 (PDD) | 天蓝色 (Cyan) #00BFFF | 中粗 ~2px | 逆袭黑马，走势最戏剧性 |
| 线 4 | 美团 (Meituan) | 青绿色 (Teal) #008080 | 中粗 ~2px | 本地生活代表 |
| 线 5 | 京东 (JD.com) | 淡青色 (Light Cyan) #66CCCC | 细线 ~1.5px | 电商第二梯队 |
| 线 6 | 百度 (Baidu) | 淡紫色 (Lavender) #9999CC | 细线 ~1.5px | 搜索+AI概念代表 |

### 焦点线选择理由

选择**阿里巴巴**作为焦点线（黑色加粗），因为：
1. 曾是中国市值最高的互联网公司（2020 年超越腾讯）
2. 跌幅最为惨烈——从 8100 亿美元跌至不到 1900 亿（-76%）
3. 是反垄断第一枪的靶心（182 亿罚款）
4. 其命运转折最能代表整个中国互联网行业的兴衰叙事
5. 2025 年开始强劲反弹（+68%），故事尚未结束

### 高亮区域

- **2021 年 Q2 — 2022 年 Q4**（监管风暴 + 中概股危机）→ 浅灰色半透明垂直带
- 这是中国互联网行业从巅峰坠入谷底的核心时间窗口

### 注释标注

- **标题**："The great reset"
- **说明**："Regulatory crackdown and delisting fears wiped over $2 trillion off China's top tech companies from 2021 to 2022"

---

## 三、Midjourney 提示词

### ✅ 版本 A — 精细版（推荐首选）

```
Professional editorial line chart showing China's top internet companies market capitalization trends from 2020 to 2025, white background, no border. 6 trend lines plotted over time (X-axis: years 2020 to 2025 with quarterly intervals, Y-axis: market cap in USD billions ranging from 0 to 1000). Color scheme: bold black focal line representing Alibaba with the most dramatic decline from $810B peak to $190B trough, dark navy blue line for Tencent as the strongest recovery story reaching $510B, cyan line for PDD showing a dramatic collapse then surge to rival Alibaba, teal line for Meituan with volatile swings, light cyan for JD.com, and lavender for Baidu at the lowest range. Lines have varying thickness — Alibaba is thickest in bold black as the main narrative. All lines surge upward through 2020 into early 2021 peaks, then collapse sharply from mid-2021 through 2022, with Alibaba falling the hardest. Gradual divergent recovery from 2023 onwards — Tencent leads recovery while Alibaba lags behind. A semi-transparent pale gray vertical highlight band marks the key crisis zone spanning Q2 2021 to Q4 2022 when regulatory crackdowns and delisting fears devastated valuations. Inline labels at the right end of each line in matching colors: "Tencent", "Alibaba", "PDD", "Meituan", "JD.com", "Baidu", no separate legend box. Top-right annotation block: bold Arial title "The great reset" with 2-line smaller description "Regulatory crackdown and delisting fears wiped over $2T off China's top tech companies, 2021-2022". No gridlines, minimal tick marks, clean Arial typography throughout. Wide cinematic layout, generous whitespace, data-ink ratio maximized, Economist / Financial Times editorial infographic style. --ar 16:9 --style raw --s 50 --v 6
```

### ✅ 版本 B — 基础版

```
A clean minimalist multi-line chart showing China's major internet companies market cap fluctuations from 2020 to 2025. 6 colored lines in a cool-tone palette (cyan, dark blue, teal, lavender) on a pure white background. One bold black line representing Alibaba as the focal point with the most dramatic rise-and-fall trajectory — peaking near $800B in early 2021 then crashing to under $200B. Tencent in dark navy blue shows the strongest recovery to $500B. PDD in cyan displays a dramatic V-shaped rebound. All lines peak around early 2021 and collapse sharply through 2022. A subtle light gray translucent vertical band highlights the Q2 2021 to Q4 2022 period of regulatory crackdowns and China tech selloff. Direct line labels on the right side reading "Tencent", "Alibaba", "PDD", "Meituan", "JD.com", "Baidu", no legend box. Annotation text in the upper right: bold title "The great reset" with smaller description about $2 trillion wiped from China tech valuations. Minimal axes with no gridlines, Y-axis showing market cap in USD billions. All text in Arial font. Editorial data visualization style, Financial Times aesthetic. --ar 16:9 --style raw --v 6
```

### ✅ 版本 C — 简洁版

```
Minimalist multi-line time series chart, 6 lines showing China top internet companies market cap 2020-2025, cool blue-purple palette with one bold black highlight line for Alibaba showing dramatic peak-to-trough decline from $800B to $190B, dark navy Tencent line recovering strongest to $500B, cyan PDD line with V-shaped rebound, white background, no gridlines, direct labels in Arial font (Tencent, Alibaba, PDD, Meituan, JD.com, Baidu), gray highlight band marking 2021-2022 regulatory crackdown period, editorial annotation "The great reset", Financial Times style infographic. --ar 16:9 --style raw --v 6
```

### ✅ 版本 D — 中文版

```
专业编辑型折线图，展示中国头部互联网公司2020-2025年市值波动趋势。纯白背景，无边框。6条趋势线：阿里巴巴（黑色加粗焦点线，从8100亿美元巅峰暴跌至1900亿美元谷底，跌幅最惨烈）、腾讯（深蓝色，恢复力最强，回升至5100亿美元）、拼多多（天蓝色，V型大反转后回调）、美团（青绿色，暴涨暴跌后缓慢恢复）、京东（淡青色）、百度（淡紫色，持续低迷）。所有线条在2021年初达到峰值后从年中开始暴跌，2022年跌至谷底。2023年起分化复苏，腾讯领涨，阿里落后。2021年Q2至2022年Q4区间有浅灰色半透明高亮带标注监管风暴和中概股退市危机时期。线条右端直接标注公司名称，无图例框。右上角注释：粗体标题"大重置"，小字说明"2021-2022年反垄断监管和退市恐慌导致中国科技巨头市值蒸发超2万亿美元"。无网格线，极简坐标轴，所有文字使用Arial字体，16:9宽屏横向布局，专业编辑型数据可视化风格。--ar 16:9 --style raw --v 6
```

---

## 四、使用建议

1. **推荐首选版本 A（精细版）**：信息最完整，Midjourney 对走势理解更准确
2. **如果效果不理想**：尝试版本 C（简洁版），减少干扰信息让 AI 聚焦关键走势
3. **关于市值精度**：Midjourney 无法精确渲染数值，生成的图表是"视觉示意"而非精确数据图。如需精确数据可视化，建议用 Python（matplotlib/plotly）或 Excel
4. **焦点线的替代选择**：
   - 如果想讲"韧性与恢复"的故事 → 把**腾讯**设为焦点线
   - 如果想讲"逆袭与崛起"的故事 → 把**拼多多**设为焦点线
   - 如果想讲"从巅峰到谷底"的故事 → 保持**阿里巴巴**（当前选择）
5. **参数调整**：
   - `--s 50`：风格化程度适中（减小可更写实）
   - `--v 6`：V6 模型文字渲染能力最强
   - `--style raw`：减少 Midjourney 美化倾向，更贴近真实图表风格
