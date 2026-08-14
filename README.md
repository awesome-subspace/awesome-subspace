<div align="center">

# awesome-subspace / 抽象空间

**A curated collection of surreal prompts for AI-generated video.**<br>
**一个持续收集超现实、荒诞与反直觉 AI 视频提示词的开源仓库。**

[![Stars](https://img.shields.io/github/stars/awesome-subspace/awesome-subspace?style=flat-square&logo=github&label=Stars)](https://github.com/awesome-subspace/awesome-subspace/stargazers)
[![Forks](https://img.shields.io/github/forks/awesome-subspace/awesome-subspace?style=flat-square&logo=github&label=Forks)](https://github.com/awesome-subspace/awesome-subspace/forks)
[![Contributors](https://img.shields.io/github/contributors/awesome-subspace/awesome-subspace?style=flat-square&label=Contributors)](https://github.com/awesome-subspace/awesome-subspace/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/awesome-subspace/awesome-subspace?style=flat-square&label=Last%20commit)](https://github.com/awesome-subspace/awesome-subspace/commits/main)
[![Prompts](https://img.shields.io/badge/curated_prompts-70%2B-2ea44f?style=flat-square)](./prompts/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2ea44f?style=flat-square)](CONTRIBUTING.md)

[浏览提示词](./prompts/) · [Browse prompts](./prompts/) · [贡献指南](CONTRIBUTING.md) · [Prompt template](./prompts/TEMPLATE.md)

</div>

---

## 项目简介 / About

`awesome-subspace` 收集能够直接用于 AI 视频生成的抽象提示词。这里的“抽象”不是随机堆砌关键词，而是通过清晰的主体、违反常识的运动、可执行的镜头语言和恰到好处的反转，让模型生成真正有记忆点的画面。

`awesome-subspace` is a curated prompt library for surreal AI video generation. Instead of throwing random keywords together, each prompt combines a clear subject, impossible motion, usable camera direction, and a deliberate visual payoff.

适合 / Built for:

- 文生视频与图生视频实验 / Text-to-video and image-to-video experiments
- Meme、荒诞短片与视觉概念测试 / Memes, absurd shorts, and visual concept studies
- Seedance、Kling、Vidu、Sora、Runway 等工具 / Major Chinese and international video models
- 中文创作，也欢迎英文或双语提示词 / Chinese-first, with English and bilingual prompts welcome

## 快速开始 / Quick Start

1. 在下方分类中选择一个方向 / Pick a collection below.
2. 打开提示词文件，复制代码块内容 / Open a prompt file and copy a code block.
3. 粘贴到视频生成工具，按需添加时长、画幅和镜头参数 / Paste it into your video model and add duration, aspect ratio, or camera controls if needed.
4. 生成效果不错？欢迎提交你的版本 / Got a strong result? Contribute your variation.

```text
主体 Subject
+ 荒诞事件 Impossible event
+ 运动过程 Motion
+ 镜头与质感 Camera and texture
+ 最后反转 Final payoff
```

> 提示 / Tip: 当模型把画面拍得过于精致时，尝试加入“固定监控机位、廉价安卓手机画质、自动曝光抽搐、不要电影感”等限制。<br>
> If the model makes everything too polished, explicitly request CCTV framing, cheap phone footage, unstable auto-exposure, or no cinematic lighting.

## 提示词分类 / Collections

| 分类 / Collection | 目录 / Path | 内容 / Focus |
|---|---|---|
| 奶龙专区 / Nailong | [`prompts/nailong/`](./prompts/nailong/) | Meme 角色、严肃铺垫与突然犯病；需要参考图 / Character memes with deadpan setups; reference image required |
| 垃圾抽象 / Trashcore | [`prompts/trashcore/`](./prompts/trashcore/) | 70 条低清废片、五毛特效和无意义反转 / 70 lo-fi prompts with cheap effects and pointless twists |
| 赛博抽象 / Cyber | [`prompts/cyber/`](./prompts/cyber/) | 数字空间、霓虹城市与故障美学 / Digital spaces, neon cities, and glitches |
| 自然异变 / Nature | [`prompts/nature/`](./prompts/nature/) | 生物、植物与自然规律的超现实变形 / Surreal mutations of living systems and natural laws |
| 日常错位 / Daily | [`prompts/daily/`](./prompts/daily/) | 熟悉场景中的逻辑崩塌 / Familiar places behaving impossibly |
| 宇宙漫游 / Cosmos | [`prompts/cosmos/`](./prompts/cosmos/) | 宇宙、虚空、尺度和维度错乱 / Space, voids, scale shifts, and dimensional anomalies |
| 古典重构 / Classical | [`prompts/classical/`](./prompts/classical/) | 古典意象的当代抽象演绎 / Contemporary surreal takes on classical imagery |
| 混沌综合 / Chaos | [`prompts/chaos/`](./prompts/chaos/) | 无法归类的跨题材混搭 / Cross-genre concepts that resist classification |

### 奶龙子分类 / Nailong Series

奶龙系列建议上传角色参考图，完整说明见 [Nailong 使用指南](./prompts/nailong/README.md)。

The Nailong series works best with a character reference image. See the [Nailong guide](./prompts/nailong/README.md).

| 子分类 / Series | 目录 / Path | 核心笑点 / Core gag |
|---|---|---|
| 美食冲突 / Cooking Fight | [`cooking-fight/`](./prompts/nailong/cooking-fight/) | 抢饭引发的笨拙格斗 / Clumsy fights over food |
| 存在主义 / Existential | [`existential/`](./prompts/nailong/existential/) | 前 90% 严肃，最后 10% 犯病 / Serious setup, ridiculous ending |
| 时尚走秀 / Fashion | [`fashion/`](./prompts/nailong/fashion/) | 高奢视觉与卡通物理失误 / Luxury visuals versus cartoon physics |
| 宇宙降临 / Cosmic | [`cosmic/`](./prompts/nailong/cosmic/) | 史诗末日被一份外卖瓦解 / Epic doom interrupted by takeaway food |
| 纪录片 / Documentary | [`documentary/`](./prompts/nailong/documentary/) | 自然纪录片与次元反差 / Nature-documentary realism with a dimensional mismatch |
| 一句话抽象 / One-liners | [`crossover/`](./prompts/nailong/crossover/) | 一句话完成铺垫和反转 / Setup and payoff in one sentence |

### 垃圾抽象子分类 / Trashcore Series

| 子分类 / Series | 提示词 / Prompts | 入口 / Path |
|---|---:|---|
| 监控录像事故 / Surveillance Failures | 10 | [`surveillance-failures.md`](./prompts/trashcore/surveillance-failures.md) |
| 五毛商业广告 / Cheap Commercials | 10 | [`cheap-commercials.md`](./prompts/trashcore/cheap-commercials.md) |
| 乡镇舞台奇观 / County Stage | 10 | [`county-stage.md`](./prompts/trashcore/county-stage.md) |
| 职场系统失控 / Office Malfunctions | 10 | [`office-malfunctions.md`](./prompts/trashcore/office-malfunctions.md) |
| 食物邪典现场 / Food Abominations | 10 | [`food-abominations.md`](./prompts/trashcore/food-abominations.md) |
| 公共空间迷惑行为 / Public-space Nonsense | 10 | [`public-space-nonsense.md`](./prompts/trashcore/public-space-nonsense.md) |
| 阴间便民服务大厅 / Underworld Service Hall | 10 | [`underworld-service-hall.md`](./prompts/trashcore/underworld-service-hall.md) |

## 精选提示词 / Featured Prompts

### 时间戳下班 / The Timestamp Clocks Out

```text
空仓库监控画面，场景完全静止，只有右上角时间戳突然从屏幕上掉下来，
像实体数字一样摔在地上。清洁工进来扫走数字，画面从此停在 18:00:00。
```

`trashcore` · `CCTV` · `低清 / lo-fi` · [查看合集 / Open collection](./prompts/trashcore/surveillance-failures.md)

### 赛博城市溶解 / Melting Cyber City

```text
A hyper-dense cyberpunk city slowly melts like wax under an invisible sun,
neon signs dripping into rivers of light, pedestrians unaware as the streets
fold upward into a Mobius strip, looping forever, camera drifting forward
through the impossible geometry, glitchy ambient soundtrack.
```

`cyber` · `城市 / city` · `循环 / loop` · [查看完整提示词 / Open prompt](./prompts/cyber/melting-city.md)

### 奶龙：最后的希望 / Nailong: The Last Hope

```text
世界末日后的上海，一个巨型奶龙从云层缓缓降落，全球媒体直播，军队严阵以待。
奶龙落在城市中央，所有人屏住呼吸。
它低头，从肚子后面掏出一份外卖，坐在废墟上开始吃饭。
```

`nailong/cosmic` · `参考图 / reference required` · [查看完整提示词 / Open prompt](./prompts/nailong/cosmic/last-hope.md)

## 工具兼容性 / Model Compatibility

提示词没有绑定特定模型。实际效果取决于模型版本、生成时长、参考图和随机种子。

Prompts are model-agnostic. Results vary by model version, duration, reference image, and seed.

| 工具 / Model | 适合场景 / Strength | 角色参考 / Character reference |
|---|---|---|
| Seedance 2.0 / 即梦 | 中文理解、复杂运动、短视频节奏 / Chinese prompts, motion, short-form pacing | 支持 / Yes |
| Kling / 可灵 | 主体一致性、真实运动 / Subject consistency and realistic motion | 支持 / Yes |
| Vidu | 角色稳定、参考图工作流 / Stable characters and reference workflows | 支持 / Yes |
| Sora | 开放式概念与空间变化 / Open-ended concepts and spatial transformations | 视版本而定 / Version-dependent |
| Runway | 镜头控制与电影质感 / Camera control and cinematic output | 视版本而定 / Version-dependent |

> 仓库中的“推荐工具”表示作者认为适合，并不代表每条提示词都经过所有平台的系统测试。<br>
> A recommended model is an author suggestion, not a claim that every prompt has been systematically benchmarked.

## 仓库结构 / Repository Structure

```text
awesome-subspace/
├── prompts/
│   ├── nailong/       # Character meme series / 角色 Meme 系列
│   ├── trashcore/     # 70 lo-fi prompts / 70 条垃圾抽象提示词
│   ├── cyber/         # Cyber surrealism / 赛博抽象
│   ├── nature/        # Mutated nature / 自然异变
│   ├── daily/         # Everyday absurdity / 日常错位
│   ├── cosmos/        # Cosmic concepts / 宇宙漫游
│   ├── classical/     # Classical remixes / 古典重构
│   ├── chaos/         # Mixed chaos / 混沌综合
│   └── TEMPLATE.md    # Contribution template / 投稿模板
├── CONTRIBUTING.md
└── README.md
```

## 贡献 / Contributing

欢迎原创提示词、现有提示词优化、新分类和真实生成反馈。

Original prompts, refinements, new collections, and generation feedback are welcome.

1. Fork 并创建分支 / Fork the repository and create a branch.
2. 在对应分类中新建 Markdown 文件 / Add a Markdown file to the appropriate collection.
3. 按照 [提示词模板 / prompt template](./prompts/TEMPLATE.md) 填写内容。
4. 提交 Pull Request，并说明测试工具与预期效果 / Open a pull request with the model used and expected result.

开始前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

### 质量标准 / Quality Bar

- 至少包含一个违反物理规律或日常逻辑的元素 / Include at least one impossible or illogical event.
- 描述可见的运动、变化或镜头过程 / Describe visible motion, transformation, or camera behavior.
- 保持可执行，避免只堆叠风格关键词 / Keep it actionable rather than stacking style keywords.
- 原创或明确注明来源 / Submit original work or clearly credit the source.
- 不包含违法、色情、歧视或伤害性内容 / No illegal, sexual, discriminatory, or harmful content.

## 社区 / Community

- 发现问题或有分类建议，请提交 [Issue](https://github.com/awesome-subspace/awesome-subspace/issues)。
- 想补充或改进提示词，请直接提交 [Pull Request](https://github.com/awesome-subspace/awesome-subspace/pulls)。
- Found a problem or have a collection idea? Open an [issue](https://github.com/awesome-subspace/awesome-subspace/issues).
- Want to add or improve a prompt? Send a [pull request](https://github.com/awesome-subspace/awesome-subspace/pulls).

---

<div align="center">

**如果这个仓库给了你一点荒诞灵感，欢迎 Star。**<br>
**If this repository gave you one strange idea, consider leaving a star.**

Maintained by the `awesome-subspace` community.

</div>
