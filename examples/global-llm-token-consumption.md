# 示例：全球头部大模型厂商 Token Consumption 季度对比（Q1 2023 – Q1 2026）— Midjourney 提示词

## 一、数据背景梳理

### 选取厂商

选取 6 家最具代表性的全球大模型厂商/平台，覆盖闭源、开源、中国出海三大阵营：

| 厂商 | 代表模型 | 阵营 | Token 消耗量级 |
|------|----------|------|----------------|
| OpenAI | GPT-4o / o3 / GPT-4.1 | 闭源领导者 | 第一梯队（绝对领先） |
| Google (Gemini) | Gemini 2.5 Pro / Flash | 闭源挑战者 | 第二梯队 |
| Anthropic | Claude 3.7 Sonnet / Opus | 闭源挑战者 | 第三梯队 |
| Meta (Llama) | Llama 3.1 / 3.2 / 4 | 开源领导者 | 第四梯队（开源生态聚合） |
| DeepSeek | DeepSeek-V3 / R1 | 中国出海黑马 | 第五梯队（2025 爆发） |
| Mistral | Mistral Large / Medium | 欧洲开源代表 | 第六梯队 |

### Token 消耗量季度走势估算（单位：万亿 tokens/季度）

> **说明**：各厂商未公开精确 token 消耗数据，以下基于公开收入数据（OpenAI 2024 年收入约 $3.7B→2025 年 ARR ~$12.7B；Anthropic 2024 年底月收入 ~$8000 万→2025 年预计 $22-37 亿；Google Cloud AI 收入增长；DeepSeek 2025 年 1 月爆发）、API 定价、Poe 平台使用份额报告（GPT-4o 35.8%、Gemini ~10%、Claude ~15%→5%、Llama ~8%）以及行业分析师估计反推。

| 季度 | OpenAI | Google Gemini | Anthropic Claude | Meta Llama | DeepSeek | Mistral |
|------|--------|---------------|------------------|------------|----------|---------|
| Q1 2023 | 2.0 | 0.1 | 0.2 | 0.3 | — | — |
| Q2 2023 | 4.5 | 0.3 | 0.5 | 0.8 | — | 0.1 |
| Q3 2023 | 7.0 | 0.8 | 1.0 | 1.5 | — | 0.2 |
| Q4 2023 | 10.0 | 1.5 | 1.8 | 2.5 | 0.1 | 0.4 |
| Q1 2024 | 15.0 | 3.0 | 3.0 | 4.0 | 0.2 | 0.8 |
| Q2 2024 | 22.0 | 5.5 | 5.0 | 6.0 | 0.5 | 1.2 |
| Q3 2024 | 32.0 | 9.0 | 7.5 | 9.0 | 1.0 | 1.8 |
| Q4 2024 | 45.0 | 14.0 | 10.0 | 13.0 | 2.0 | 2.5 |
| Q1 2025 | 60.0 | 22.0 | 12.0 | 18.0 | 12.0 | 3.5 |
| Q2 2025 | 80.0 | 32.0 | 14.0 | 25.0 | 20.0 | 4.5 |
| Q3 2025 | 105.0 | 45.0 | 18.0 | 35.0 | 30.0 | 6.0 |
| Q4 2025 | 135.0 | 60.0 | 22.0 | 48.0 | 42.0 | 8.0 |
| Q1 2026 | 170.0 | 80.0 | 28.0 | 65.0 | 58.0 | 10.0 |

### 关键事件节点

- **Q1 2023**：ChatGPT 爆发后 API 正式开放（GPT-3.5 Turbo），OpenAI 一骑绝尘
- **Q2 2023**：Anthropic 发布 Claude 2，Google 发布 PaLM 2 / Bard API，竞争启动
- **Q3 2023**：Meta 开源 Llama 2，开源生态 token 消耗开始加速
- **Q4 2023**：GPT-4 Turbo 发布（128K 上下文），长文本推动 token 量飙升；Mistral 7B 发布
- **Q1 2024**：Claude 3 系列发布（Opus/Sonnet/Haiku），Anthropic 用量暴涨；Gemini 1.5 Pro 发布
- **Q2 2024**：GPT-4o 发布，OpenAI 免费用户大幅增加；Llama 3 开源
- **Q3 2024**：OpenAI o1 推理模型上线，每次推理消耗 token 量大幅增加；Gemini 使用量加速
- **Q4 2024**：GPT-4o mini 降价引爆 API 调用量；DeepSeek-V3 发布引发关注
- **Q1 2025（⬆️ DeepSeek 爆发）**：DeepSeek-R1 全球爆火，API 充值一度暂停；推理模型使 token 消耗倍增
- **Q2-Q4 2025**：OpenAI GPT-4.1 系列 + o3；Gemini 2.5 Pro 快速追赶；DeepSeek 持续高增长
- **Q1 2026**：AI Agent 时代到来，多步推理任务推动全行业 token 消耗加速

---

## 二、图表设计规划

### 数据线设计（6 条线）

| 线条 | 对应厂商 | 颜色 | 线条粗细 | 选择理由 |
|------|----------|------|----------|----------|
| **焦点线** | OpenAI | **黑色 (Bold Black)** | 加粗 ~3px | 绝对领导者，用量始终最高，增长曲线最陡 |
| 线 2 | Google Gemini | 深蓝色 (Dark Navy) #003399 | 中粗 ~2px | 最强挑战者，2025 年加速追赶 |
| 线 3 | DeepSeek | 天蓝色 (Cyan) #00BFFF | 中粗 ~2px | 2025 年黑马，从近乎零到第三名的逆袭 |
| 线 4 | Meta Llama | 青绿色 (Teal) #008080 | 中粗 ~2px | 开源生态聚合，稳步增长 |
| 线 5 | Anthropic Claude | 淡青色 (Light Cyan) #66CCCC | 细线 ~1.5px | 从领先到掉队，增长放缓 |
| 线 6 | Mistral | 淡紫色 (Lavender) #9999CC | 细线 ~1.5px | 欧洲代表，体量最小但稳定增长 |

### 焦点线选择理由

选择 **OpenAI** 作为焦点线（黑色加粗），因为：
1. 全程绝对领先，始终占据 40-50% 的市场份额
2. 增长曲线最为陡峭 — 从 Q1 2023 的 2 万亿 tokens/季到 Q1 2026 的 170 万亿 tokens/季（85 倍增长）
3. 是 LLM API 市场的定义者和价格制定者
4. 每次新模型发布（GPT-4o、o1、GPT-4.1）都伴随 token 消耗量的阶梯式跳跃
5. 其增长曲线的斜率变化反映了整个行业的发展节奏

### 高亮区域

- **Q4 2024 — Q2 2025**（AI 推理革命 + DeepSeek 爆发）→ 浅灰色半透明垂直带
- 这是 token 消耗增速最快的时期：推理模型上线使单次调用 token 消耗增加 5-10 倍，DeepSeek 以极低价格引爆中国市场

### 注释标注

- **标题**："The inference explosion"
- **说明**："Reasoning models and DeepSeek's breakthrough drove global LLM token consumption past 300 trillion tokens/quarter by late 2025"

---

## 三、Midjourney 提示词

### ✅ 版本 A — 精细版（推荐首选）

```
Professional editorial line chart showing global LLM token consumption by major AI providers from Q1 2023 to Q1 2026, white background, no border. 6 trend lines plotted over time (X-axis: quarterly intervals Q1'23 to Q1'26, Y-axis: trillion tokens per quarter ranging from 0 to 180). Specific data points for each line — Bold black focal line "OpenAI": 2T in Q1'23, 4.5T in Q2'23, 7T in Q3'23, 10T in Q4'23, 15T in Q1'24, 22T in Q2'24, 32T in Q3'24, 45T in Q4'24, 60T in Q1'25, 80T in Q2'25, 105T in Q3'25, 135T in Q4'25, 170T in Q1'26 — exponential growth curve steepening over time. Dark navy blue line "Google Gemini": starts at 0.1T in Q1'23, grows slowly to 1.5T by Q4'23, accelerates to 14T by Q4'24, then surges to 80T by Q1'26 as second-place challenger. Cyan line "DeepSeek": absent until Q4'23 at 0.1T, barely visible through Q3'24 at 1T, then explodes from 2T in Q4'24 to 12T in Q1'25, reaching 58T by Q1'26 — the most dramatic S-curve on the chart. Teal line "Meta Llama": starts at 0.3T in Q1'23, steady climb through open-source adoption to 13T by Q4'24 and 65T by Q1'26. Light cyan line "Anthropic Claude": starts at 0.2T in Q1'23, grows steadily to 10T by Q4'24, but growth slows visibly to only 28T by Q1'26 — overtaken by DeepSeek and Llama. Lavender line "Mistral": appears from Q2'23, stays at the bottom growing slowly from 0.1T to 10T by Q1'26. Lines have varying thickness — OpenAI is thickest in bold black as the dominant leader, Google and DeepSeek medium thickness, Mistral thinnest. All lines show exponential acceleration with OpenAI consistently on top. A semi-transparent pale gray vertical highlight band marks Q4 2024 to Q2 2025 when reasoning models and DeepSeek's breakout drove the steepest acceleration. Inline labels at the right end of each line in matching colors: "OpenAI", "Google Gemini", "DeepSeek", "Meta Llama", "Anthropic", "Mistral", no separate legend box. Top-right annotation block: bold Arial title "The inference explosion" with 2-line smaller description "Reasoning models and DeepSeek's breakthrough drove global LLM token consumption past 300T tokens/quarter by late 2025". No gridlines, minimal tick marks, clean Arial typography throughout. Wide cinematic layout, generous whitespace, data-ink ratio maximized, editorial infographic style. --ar 16:9 --style raw --s 50 --v 6
```

### ✅ 版本 B — 基础版

```
A clean minimalist multi-line chart showing global LLM token consumption in trillion tokens per quarter from Q1 2023 to Q1 2026. 6 colored lines on a pure white background. Bold black line "OpenAI" starts at 2T, grows exponentially to 10T in Q4'23, 45T in Q4'24, 135T in Q4'25, 170T in Q1'26 — always the highest line. Dark navy blue "Google Gemini" starts near zero, accelerates from 3T in Q1'24 to 60T in Q4'25, reaching 80T by Q1'26 as closest challenger. Cyan "DeepSeek" is the breakout story — invisible until late 2024, then rockets from 2T to 58T by Q1'26 in an explosive S-curve. Teal "Meta Llama" grows steadily from 0.3T to 65T via open-source adoption. Light cyan "Anthropic Claude" grows from 0.2T to 10T by Q4'24 but flattens to only 28T by Q1'26, overtaken by DeepSeek and Llama. Lavender "Mistral" stays lowest at 10T by Q1'26. Gray highlight band marks Q4'24 to Q2'25 reasoning model explosion period. Direct line labels on the right side, no legend box. Annotation in upper right: bold title "The inference explosion" with description about 300T+ tokens/quarter. Minimal axes, no gridlines, Y-axis 0 to 180T. All text in Arial font. Editorial data visualization style. --ar 16:9 --style raw --v 6
```

### ✅ 版本 C — 简洁版

```
Minimalist multi-line chart, 6 lines, global LLM token consumption in trillion tokens/quarter Q1'23-Q1'26, Y-axis 0-180T. Bold black "OpenAI" 2T→10T→45T→135T→170T exponential growth, always highest. Dark navy "Google Gemini" 0.1T→1.5T→14T→60T→80T accelerating challenger. Cyan "DeepSeek" 0→0.1T→2T→42T→58T explosive S-curve breakout from 2025. Teal "Meta Llama" 0.3T→2.5T→13T→48T→65T steady open-source growth. Light cyan "Anthropic" 0.2T→1.8T→10T→22T→28T slowing growth overtaken. Lavender "Mistral" 0.1T→0.4T→2.5T→8T→10T smallest player. Gray highlight band Q4'24-Q2'25 marking reasoning model explosion. Direct labels in Arial, no gridlines, white background, annotation "The inference explosion", editorial infographic style. --ar 16:9 --style raw --v 6
```

### ✅ 版本 D — 中文版

```
专业编辑型折线图，展示全球头部大模型厂商2023Q1至2026Q1季度Token消耗量对比（单位：万亿tokens/季度）。纯白背景，无边框。Y轴范围0-180万亿。6条趋势线及具体数据——OpenAI（黑色加粗焦点线）：Q1'23起步2万亿，Q4'23增至10万亿，Q2'24达22万亿，Q4'24达45万亿，Q1'25跃至60万亿，Q4'25达135万亿，Q1'26冲上170万亿，指数级增长始终最高。Google Gemini（深蓝色）：Q1'23仅0.1万亿，Q1'24增至3万亿，Q4'24达14万亿，Q4'25飙升至60万亿，Q1'26达80万亿，追赶势头最猛。DeepSeek（天蓝色）：2023年几乎为零，Q4'24才2万亿，Q1'25爆发至12万亿，Q4'25达42万亿，Q1'26达58万亿，最惊人的S型曲线爆发。Meta Llama（青绿色）：开源生态聚合，Q1'23起步0.3万亿，Q4'24达13万亿，Q1'26达65万亿，稳步增长。Anthropic Claude（淡青色）：Q1'23起步0.2万亿，Q4'24达10万亿，但增速明显放缓，Q1'26仅28万亿，被DeepSeek和Llama反超。Mistral（淡紫色）：体量最小，Q2'23起步0.1万亿，Q1'26达10万亿。Q4'24至Q2'25区间有浅灰色半透明高亮带标注推理模型革命与DeepSeek爆发期。线条右端直接标注厂商名称，无图例框。右上角注释：粗体标题"推理大爆发"，小字说明"推理模型和DeepSeek的突破推动全球LLM Token消耗在2025年底突破每季度300万亿"。无网格线，极简坐标轴，所有文字使用Arial字体，16:9宽屏横向布局，专业编辑型数据可视化风格。--ar 16:9 --style raw --v 6
```

---

## 四、使用建议

1. **推荐首选版本 A（精细版）**：每条线每个季度都有具体数值，Midjourney 能更好理解各线的相对位置和增长速度
2. **如果效果不理想**：尝试版本 C（简洁版），用箭头符号 → 标注关键节点数据
3. **关于 Token 精度**：数据基于公开收入、API 定价和市场份额报告反推估算，并非官方披露的精确值。Midjourney 生成的是"视觉示意"而非精确数据图。如需精确数据可视化，建议用 Python（matplotlib/plotly）
4. **焦点线的替代选择**：
   - 如果想讲"从零到巨人"的黑马故事 → 把 **DeepSeek** 设为焦点线
   - 如果想讲"巨头追赶"的竞争故事 → 把 **Google Gemini** 设为焦点线
   - 如果想讲"开源吞噬世界"的故事 → 把 **Meta Llama** 设为焦点线
   - 如果想讲"绝对领导者"的统治故事 → 保持 **OpenAI**（当前选择）
5. **注意曲线形态**：
   - OpenAI：持续指数增长（每季度 ~30-40% 环比增长）
   - DeepSeek：典型 S 型爆发曲线（前平后陡）
   - Anthropic：增长放缓曲线（从领先到被超越）
   - 这三条线的对比构成了最有叙事张力的视觉冲突
6. **参数调整**：
   - `--s 50`：风格化程度适中（减小可更写实）
   - `--v 6`：V6 模型文字渲染能力最强
   - `--style raw`：减少 Midjourney 美化倾向，更贴近真实图表风格
