# FANTASY CHARACTER VISUAL DNA

### 角色视觉 DNA · 让想象先被看见

从一句角色想法，到具有独立辨识度、可信材质与持续开发能力的视觉形象。

![Character Design · Cinematic Realism · ZH / EN · Reference Guided](assets/badges.svg)

| 孙悟空 · 白袍造型 | 猪八戒 · 圆重猪妖 | 哪吒 · 红绫与动态 |
| :---: | :---: | :---: |
| ![白袍孙悟空](assets/examples/sun-wukong-white-robes.jpg) | ![完整猪妖体态的猪八戒](assets/examples/zhu-bajie-heavy-form.jpg) | ![红绫与动态轮廓的哪吒](assets/examples/nezha-red-ribbons.jpg) |

**[快速开始](#快速开始) · [设计规则](#设计规则) · [创作工作流](#创作工作流) · [完整图库](docs/GALLERY.md) · [安装](#安装与调用) · [English](#english-overview)**

## 这是什么

AI 可以很快生成一个复杂的角色，但复杂并不等于有设计。常见问题是：换了名字，还是同一张脸；换了题材，还是同一套盔甲；画面看起来华丽，角色却缺少能够被记住的特征。

**FANTASY CHARACTER VISUAL DNA** 从身份、剪影、体型、面部、服装、材质、道具和行为出发，帮助你明确：角色是谁、为什么这样穿、什么必须保留、什么可以变化，再转成适合图像模型执行的提示词和修改指令。

默认追求电影级写实：真实骨相与皮肤毛发、清楚的形体关系、可信的服装结构、具有重量与功能的道具。用户指定动画、插画或其他方向时，以当前任务为准。

这是供助手读取的设计规则与工作流，**本身不是图像模型**。它帮助设计、组织与检查，不承诺跨模型的绝对一致或一键复现。

## 可以做什么

| 需求 | 对应成果 |
| --- | --- |
| 从一句话开始设计角色 | 简短定位、核心识别点、可直接使用的提示词 |
| 神话、志怪、小说与经典角色重构 | 原型锚点、创新方向与可辨识的新形象 |
| 根据参考图继续开发 | 角色锁定清单与参考图分工 |
| 系列角色、同一阵营或群像 | 世界共性与人物差异矩阵 |
| 修正太脏、过度华丽、模板化等问题 | 聚焦具体部位的修改指令 |
| 建立后续素材 | 按需发展的三视图、头肩特写、表情与道具资产 |

## 快速开始

不必先填一张很长的表格。角色名称、一个方向、一个最重要的限制，通常就足够开始。

### 从角色想法开始

```text
使用 $fantasy-character-visual-dna。
设计一个 2000 年后的黑熊精，保留完整熊妖体态。
服装要有现代时尚感，也能看出袈裟的结构意向。
科技元素克制，背景简单，先给我一版中英文角色提示词。
```

### 保持参考，只改局部

```text
以图 1 为角色基准，保留脸型、发色、体型和服装主体。
图 2 只参考左前臂与武器的结构。
给我一段精简的 Banana 中文修改提示词，不生成图片。
```

### 形成可复用资产

```text
把已经确认的角色做成正面、侧面、背面的全身三视图。
16:9，干净灰底，比例一致，无文字，不能重新设计角色。
```

### 跨题材设计

```text
设计三个同一世界观的西方经典怪物。
让他们在体型、年龄、剪影、服装和动作上有明显区别。
先给角色差异表，再分别给英文提示词，不要套东方神话装饰。
```

你只要提示词时，Skill 只交付文字；你要求直接生成图片时，助手才使用当前环境实际提供的图像能力。

## 设计规则

| 规则 | 它改变什么 |
| --- | --- |
| 身份先成立 | 把“神秘、霸气、高级”变成具体可见的角色特征 |
| 种族不退化 | 写实兽妖保留完整物种结构，避免普通人加动物鼻子 |
| 轮廓有区别 | 避免全员宽肩、披风、大腰带、尖刺装甲 |
| 面部有性格 | 以骨相、年龄、五官关系和情绪区分新角色 |
| 衣物可理解 | 层次、厚薄、连接与受力有逻辑 |
| 细节有主次 | 重点集中在脸、道具和识别区域，减少随机碎饰 |
| 磨损有原因 | 使用痕迹与实际接触、受力位置对应 |
| 科技有用途 | 局部装置服务身份、能力或功能，避免通用机械模板 |
| 参考有分工 | 身份图、衣服图、材质图与构图图各司其职 |
| 修改有边界 | 用户只改局部时，保存其余已确认内容 |
| 资产有基准 | 三视图与表情共享同一身份、结构和尺度 |
| 检查有证据 | 看不清的数量与被遮挡结构不宣布“完全一致” |

完整执行规则见 [SKILL.md](SKILL.md)。细节、模板与项目预设按需读取，不必每次把整套文档全部塞进提示词。

### 通用规则与赛博西游分开

通用层负责角色辨识、身体、材质、构图和一致性。[赛博西游预设](references/cyber-journey-preset.md)只在相应项目启用，保留猪八戒的完整猪妖体态、沙僧的魁梧与红发红须等已确认方向。

西方、现代或轻奇幻角色使用自身语境。某张示例图的华丽装甲、环状构件、题字或红印章，也不会自动成为全部新角色的固定要求。

## 创作工作流

| 阶段 | 要完成的判断 | 可以如何配合工具 |
| --- | --- | --- |
| 建立角色 | 身份、身体、脸、衣服与少量关键特征 | ChatGPT / 支持 Skill 的助手整理需求和参考 |
| 探索视觉 | 比例、构图、材质与风格方向 | Midjourney 或其他生成模型进行视觉探索 |
| 选定基准 | 选出形象准确的一张，记录固定特征 | 保存图片与简短角色 DNA 清单 |
| 局部修正 | 找准脸、衣物、武器或结构的具体问题 | Banana 或支持参考图编辑的模型修正 |
| 角色资产化 | 让已确认形象进入下一步内容生产 | 三视图、头肩、表情、道具与场景应用 |

实际工作可以在这些环节之间往返。角色还没稳定时，不急着批量展开全部素材；工具也可以根据你的使用环境替换。

### 使用参考与参数时

- 明确图 1 锁定谁、图 2 参考什么，避免多图无差别融合。
- Describe 或视觉反推可以帮助提取外观语言，但不能恢复原始提示词和全部隐藏信息。
- 模型版本、参考图参数、权重与风格参数按实际使用版本确认，Skill 不固定捏造一个通用参数组合。
- 风格可以继续探索；脸、发色、服装结构等已确认字段应保持。

## 示例图

| 蝎子精 · 物种轮廓 | 太上老君 · 长者形象 | 弗兰肯斯坦怪物 · 重量感 |
| :---: | :---: | :---: |
| ![蝎尾围合人物的造型](assets/examples/scorpion-demoness.jpg) | ![长白发须与灰白长袍的太上老君](assets/examples/taishang-laojun.jpg) | ![重体量怪物与材质对比](assets/examples/frankenstein-monster.jpg) |

[查看完整的 19 张示例及逐图说明 →](docs/GALLERY.md)

示例由仓库维护者提供，用于展示角色辨识、轮廓、材质和关系设计。它们不是本版本规则的生图测试记录，也不保证可以原样复现。

图库保留原始文件名称记录，并对名称与可见画面不一致的案例作了说明。例如文件名含“无头骑士”的图中，主体肩上仍有头部，因此仅作为哥特造型探索展示。

## 安装与调用

### Codex CLI

将仓库放入用户技能目录，确保 `SKILL.md` 位于技能文件夹的根部。

**Windows PowerShell（默认用户目录）：**

```powershell
git clone https://github.com/dacnay816y62-hub/fantasy-character-visual-dna-skill.git "$env:USERPROFILE\.codex\skills\fantasy-character-visual-dna"
```

**macOS / Linux：**

```bash
git clone https://github.com/dacnay816y62-hub/fantasy-character-visual-dna-skill.git "${CODEX_HOME:-$HOME/.codex}/skills/fantasy-character-visual-dna"
```

如果自定义了 Codex 数据目录，请改成相应目录。目标文件夹已存在时，不重复覆盖；先确认里面是否就是这个仓库。

安装后在支持技能调用的对话中使用 `$fantasy-character-visual-dna`，或直接提出与它匹配的角色设计需求。

### 其他支持读取文件的助手

让助手读取 [SKILL.md](SKILL.md)，并按任务读取其链接的参考文件。只粘贴 README 不能替代完整规则。不同产品的导入入口和可用图像工具各不相同，本仓库不宣称已在所有环境完成安装测试。

## 文件导航

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | 技能入口、任务路由与关键约束 |
| [设计规则](references/design-rules.md) | 视觉 DNA、物种、脸、衣物、材质、构图与多角色 |
| [参考与编辑](references/reference-and-editing.md) | 参考图分工、冲突处理与局部修改 |
| [资产一致性](references/asset-consistency.md) | 三视图、头肩、表情与角色基准 |
| [提示词编译](references/prompt-compiler.md) | 中英输出、编辑模板与角色示例 |
| [赛博西游预设](references/cyber-journey-preset.md) | 项目专用设定，按需启用 |
| [质量与纠偏](references/quality-and-iteration.md) | 常见失败、反馈转译与检查边界 |
| [完整图库](docs/GALLERY.md) | 19 张示例、设计说明及原始名称对应表 |
| [仓库元数据](docs/repository-metadata.json) | About 与 Topics 的维护记录 |

## 常见问题

**会不会所有角色都被做成赛博西游？**

不会。项目预设按需加载，通用规则不绑定一种文化或题材。

**能否使用非写实风格？**

可以。用户当前指定的画风优先，身份、结构和跨图关系仍然需要一致。

**三视图是不是把同一段提示词生成三遍？**

不是。三个角度共享角色基准和尺度，只改变观察方向，并对照头发、衣物、饰物、道具及身体结构。

**为什么角色总是太脏或太华丽？**

优先检查碎饰、重复雕花、随机划痕和暗部密度。让比例、材质对比与核心道具承担设计，而不是继续加装饰。

**能完全复现示例吗？**

不能据此承诺。图像结果还受到输入参考、模型、参数和后续编辑影响。没有生成记录时，反推内容会标为重建提示词。

**这个项目是否已经完成全面生图测试？**

没有。文件结构检查和文字行为验证不能代替实际生图验证。请结合自己的模型与任务检验角色识别和资产一致性。

## 反馈

欢迎通过仓库的 Issues 提供具体输入、模型环境、结果图与希望修正的部位。说明哪些内容必须保留、哪些需要改变，会比单独一句“效果不好”更容易帮助改进规则。

## 关于 FANTASY

**FANTASY / 梵想美学**

**让想象先被看见。**

把视觉判断、创作经验与模型工具组织成可持续使用的方法。Skill 帮助搭建和迭代，角色最终是否成立，仍然需要创作者自己的判断。

本仓库公开展示规则与案例，未附加许可证。示例图保留原有文字与标识。

## English overview

**FANTASY CHARACTER VISUAL DNA** is a reusable character design skill for cinematic realism, mythology reinterpretation, bilingual prompts, reference-guided edits and consistent character assets.

It starts from identity, species anatomy, silhouette, proportions, facial structure, clothing, materials, signature objects and behavior. It helps an assistant produce a coherent character concept and carry the selected design into focused edits, turnarounds and expression sheets.

- The user's current style and deliverable take priority over defaults.
- Chinese mythology and cyber Journey to the West are optional project settings, not universal templates.
- Prompt-only requests remain text-only.
- Existing identity references are preserved during focused edits.
- Model-specific parameters must be verified for the actual version in use.
- The gallery contains 19 creator-supplied examples, not a claim of reproducible benchmark results.

Start with [SKILL.md](SKILL.md), read only the relevant references, and view the [full gallery](docs/GALLERY.md).
