# 中轴夹景文化展览海报 Skill / Central Axis Framing Poster Skill

左右夹势，中轴聚焦：生成一张 9:16 强设计感文化展览海报，两侧元素表达主题，标题真正参与构图。

## 它能做什么
- 清晰稳定的竖向中轴，左右元素把视线推向中心
- 五种夹景方式：人物动作 / 光影投射 / 正负对照 / 烟雾气流 / 实体轮廓
- 标题参与构图，排法多变，不套固定四字格式
- 比普通海报更丰富的展讯信息，可选小型研究模块
- 只给主题也能用；未提供日期场馆时用虚构占位或省略，不伪造真实展览

## 安装
**作为 Agent Skill（Claude Code / Cursor / Codex 等）**：

```bash
git clone https://github.com/ericchan916/central-axis-framing-poster-skill.git
cp -r central-axis-framing-poster-skill ~/.claude/skills/central-axis-framing-poster
# 或 ~/.cursor/skills/、~/.codex/skills/ 等
```

**在 ChatGPT / 其他图像模型中使用**：复制 [`prompt.md`](prompt.md) 里的完整提示词，填入字段即可。

## 使用示例
```
【主题】：昆曲水袖
【夹景方式】：人物动作
```
或只写：`【主题】：斗拱`

更多示例见 [`examples/themes.md`](examples/themes.md)。

## 夹景方式
| 方式 | 做法 |
|---|---|
| 人物动作 | 姿态、水袖、布料框出中心负形 |
| 光影投射 | 两侧阴影或高光汇聚于中心 |
| 正负对照 | 原物与成品、器物与印痕形成中轴关系 |
| 烟雾气流 | 两道上升或回旋线条环绕中心 |
| 实体轮廓 | 器物、建筑或自然形态边缘围合中心 |

## English
**Central Axis Framing Poster** creates one 9:16 cultural exhibition poster built on a stable vertical axis, framed by left and right elements that express the theme, with an integrated title and museum-grade editorial info. Copy the folder into your agent's skills directory, or paste `prompt.md` into ChatGPT or any image model.

## License
MIT © 2026 Joy Robinson — 见 [LICENSE](LICENSE)。生成图片的使用请同时遵守你所用图像模型的服务条款。
