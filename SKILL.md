---
name: central-axis-framing-poster
description: 中轴夹景文化展览海报：以清晰稳定的竖向中轴为核心，左右两侧元素（人物动作 / 光影投射 / 正负对照 / 烟雾气流 / 实体轮廓）共同把视线推向中心，标题真正参与构图，信息密度高于普通海报，生成一张 9:16 强设计感文化展览海报。当用户提到"中轴夹景 / 夹景海报 / 中轴构图展览海报"时使用。Use when the user asks for a central-axis framing poster or a cultural exhibition poster where left and right elements frame a central axis — produces one premium museum-grade 9:16 poster with integrated title and editorial info.
license: MIT
---

# 中轴夹景文化展览海报 · Central Axis Framing Poster

左右夹势，中轴聚焦：两侧不是装饰，而是主题本身。
Left and right forces push the eye to a stable central axis — the sides are the theme, not decoration.

## 输入 · Inputs

```
【主题】：
【中文标题】：
【英文标题】：
【左侧元素】：
【右侧元素】：
【中轴内容】：
【夹景方式】：人物动作 / 光影投射 / 正负对照 / 烟雾气流 / 实体轮廓
【主色调】：
【辅助色】：
【日期 / 场馆】：
【画面比例】：9:16（默认）
```

## 使用规则 · Agent rules
- **不要追问，不输出分析 / Never ask, never show analysis.**
- 缺失字段根据【主题】协调补全；【夹景方式】未指定时，选最能表达主题的一种。英文标题自然地道，不逐字直译。
- **【日期 / 场馆】未提供时，不编造真实场馆，也不伪造真实展览**：使用中性、明显虚构的格式（如"2026.11.08 — 2027.02.28 / 东方工艺研究展厅"这类通用名称），或直接省略；在给用户的说明中注明该信息为占位。If date/venue is missing, never invent a real venue or fake a real exhibition — use a neutral fictional placeholder or omit it, and say so.
- 只输出一张海报；环境不能生图时，输出已填好的 [prompt.md](prompt.md) 提示词。

示例见 [examples/themes.md](examples/themes.md)。

## 核心规则 · Core rules

### 中轴与夹景 · Axis & framing
- 清晰、稳定的竖向中轴；左右元素共同把视线推向中心。
- 两侧不是单纯对称装饰，而是表达主题：人物、水袖、烟雾、器物、建筑、投影、材料轮廓，或同一主题的不同状态。

### 夹景方式 · Framing modes
| 方式 | 做法 |
|---|---|
| 人物动作 | 姿态、水袖、布料、身体曲线框出中心的负形 |
| 光影投射 | 两侧阴影或高光汇聚于中心 |
| 正负对照 | 原物与成品、器物与印痕、反刻与正印，构成中轴关系 |
| 烟雾气流 | 两道连续上升或回旋的线条环绕中心 |
| 实体轮廓 | 器物、建筑或自然形态的边缘共同围合中心 |

### 标题 · Title
- 标题是核心，并真正参与构图：大号竖排、横排、偏移、上下拆分或跨区排布；不要总用同一种四字格式。
- 文字可与主体轻微穿插、叠压、贴边，但保持可读。

### 信息密度 · Information density
- 高于普通海报：中轴、侧栏、底部安排少量展讯信息。
- 可选小型研究模块：动作轨迹、工艺步骤、气流变化、结构图解——成熟的博物馆海报 / 编辑设计。

### 色彩 · Color
3–5 个主色，大色块关系清晰（【主色调】+【辅助色】）。

### 阅读顺序 · Reading order
1. 左右视觉力量与中轴焦点
2. 标题
3. 构图方式与主题之间的关联

### 整体 · Overall
高级、清晰、完整、有层次、有冲击力。

### 避免 · Avoid
机械对称、固定模板感、PPT 式信息框、无意义装饰、斑驳噪点、模糊文字、低完成度 AI 感；虚构真实场馆或伪造真实展览。
