# 提示词编译与模板

### L. 提示词编译与输出

按可见信息的优先级组织提示词：**角色身份 → 种族与身体 → 面部毛发 → 服装材质 → 核心道具 → 动作 → 构图光线 → 必要限制**。删除重复的“超高清、史诗、高级”等堆叠词。

中英版本保持相同设定。英文是面向模型的自然描述，不必逐字翻译；不能趁翻译增加另一套武器、颜色或身份。

Midjourney 提示词把主体描述与参数分开。用户指定模型版本时保留需求，但在实际填入版本号、参考参数或权重前核对当前支持情况；不能凭经验捏造参数。无法核实则先提供无争议的主体文本，并明确参数尚未确认。

Banana 或其他编辑模型的指令要写清：底图、保留项、唯一修改目标、参考图的对应部分、边缘衔接和环境连续性。不要在一段局部修改指令中同时要求重做构图、换脸和更换全部材质。

反推图像时只描述可见特征；镜头焦距、摄影器材、生成模型与原始参数通常只能推测。将结果标为“反推 / 重建提示词”，不得伪称原始提示词。

通常输出一段简短设计定位与一组所需提示词。用户要求“精简可复制”时去掉分析过程；用户要求完整角色方案时再展开 DNA 表、设计理由与资产建议。

# 输出模板

### 新角色 · 精简模板

```text
角色定位：一句话说明身份、气质与所处环境。
核心识别：列出最需要保留的 1–3 个特征。
中文提示词：一段完整、可复制的视觉描述。
English prompt: the same character design in natural English.
参数：仅填写用户要求且当前已确认可用的参数。
```

### 局部编辑 · 精简模板

```text
以图 1 为底图，保持人物脸型、发色、体型、服装主体和当前构图。
仅修改【具体部位】为【结构、材质和连接方式】。
图 2 只参考【指定元素】，不引入图 2 的人脸、姿态或背景。
让修改区域的光线、遮挡和边缘与原图自然衔接。
保持原画幅，其他已确认元素不变。
```

### 角色基准记录 · 精简模板

```text
基准图：明确引用用户确认的图片。
身份与物种：
身体比例：
脸与毛发：
服装层次与颜色：
配件位置：以角色自身左右记录。
道具类型、数量与结构：
本次允许变化：
本次禁止变化：
尚未展示、需要推定的区域：
```

### 示例：黑熊精角色提示词（新编示范，非图库原始提示词）

```text
2000 年后的黑熊精，一位沉稳、富有阅历的完整黑熊妖行者，宽厚熊头、厚颈与圆重躯干，深色眼睛嵌在清晰的熊科骨相中，口鼻周围少量灰毛。炭黑粗织内衣外披斜向层叠的深褐袍衣，以袈裟的结构意向转成简洁的现代裁片，旧皮革斜带承托随身器物，肩部仅有少量黑化金属连接件。服装重量自然落在厚重身体上，一手扶住朴素的深色长杆兵器，站姿安稳，神态温和但有分量。全身三分之四视角，低信息密度的灰褐背景，柔和侧光，真实毛发、粗布与皮革质感，电影级写实，无文字。先保证物种和服装结构清晰，避免通用机械腰带、满身雕花与霓虹装饰。
```

```text
A black bear demon wanderer reimagined two thousand years in the future, calm and experienced, with a complete ursine anatomy: a broad bear skull, thick neck and rounded heavy torso, dark eyes set in a clearly defined bear face, sparse grey fur around the muzzle. A charcoal coarse-woven inner garment beneath a dark brown robe, its diagonal layered construction suggesting a monastic kasaya through restrained contemporary tailoring. An aged leather shoulder strap supports his belongings; only a few blackened metal connectors appear at one shoulder. The garments hang with believable weight over his substantial body. One hand rests on a simple dark pole weapon, his stance grounded and his expression gentle but imposing. Full-body three-quarter view, a quiet grey-brown background, soft side light, realistic fur, coarse cloth and worn leather, cinematic realism, no text. Keep species identity and garment construction readable, with no generic mechanical belt, excessive engraving or neon ornament.
```

该示例演示提示词组织方式。兵器未宣称还原原著；如果任务要求准确对应原著，应先核对再替换这一字段。
