<div align="center">

# awesome-subspace / 抽象空间

**一个持续收集超现实、荒诞与反直觉 AI 视频提示词的开源仓库。**

[![Stars](https://img.shields.io/github/stars/awesome-subspace/awesome-subspace?style=flat-square&logo=github&label=Stars)](https://github.com/awesome-subspace/awesome-subspace/stargazers)
[![Forks](https://img.shields.io/github/forks/awesome-subspace/awesome-subspace?style=flat-square&logo=github&label=Forks)](https://github.com/awesome-subspace/awesome-subspace/forks)
[![Contributors](https://img.shields.io/github/contributors/awesome-subspace/awesome-subspace?style=flat-square&label=Contributors)](https://github.com/awesome-subspace/awesome-subspace/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/awesome-subspace/awesome-subspace?style=flat-square&label=Last%20commit)](https://github.com/awesome-subspace/awesome-subspace/commits/main)
[![Prompts](https://img.shields.io/badge/curated_prompts-60%2B-2ea44f?style=flat-square)](./prompts/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2ea44f?style=flat-square)](CONTRIBUTING.md)

[English](README.md) | 简体中文

[浏览提示词](./prompts/) · [贡献指南](CONTRIBUTING.md) · [提示词模板](./prompts/TEMPLATE.md)

</div>

---

## 项目简介

`awesome-subspace` 收集能够直接用于 AI 视频生成的抽象提示词。这里的“抽象”不是随机堆砌关键词，而是通过清晰的主体、违反常识的运动、可执行的镜头语言和恰到好处的反转，让模型生成真正有记忆点的画面。

适合用于：

- 文生视频与图生视频实验
- Meme、荒诞短片与视觉概念测试
- Seedance、Kling、Vidu、Sora、Runway 等视频模型
- 中文与英文提示词，以及需要参考图的角色工作流

## 快速开始

1. 从下方目录中选择一个分类。
2. 打开提示词文件，复制代码块内容。
3. 粘贴到视频生成工具，按需添加时长、画幅和镜头参数。
4. 生成效果不错？欢迎贡献你的提示词或改进版本。

```text
主体
+ 荒诞事件
+ 可见的运动过程
+ 镜头与画面质感
+ 最后的反转
```

> 提示：当模型把画面拍得过于精致时，可以明确加入“固定监控机位、廉价手机画质、自动曝光抽搐、正午硬光、不要电影感”等限制。

## 提示词分类

| 分类 | 目录 | 内容 |
|---|---|---|
| 奶龙专区 | [`prompts/nailong/`](./prompts/nailong/) | Meme 角色、严肃铺垫与突然犯病；需要参考图 |
| 垃圾抽象 | [`prompts/trashcore/`](./prompts/trashcore/) | 60 条低清废片、五毛特效、尴尬表演与无意义反转 |
| 赛博抽象 | [`prompts/cyber/`](./prompts/cyber/) | 数字空间、霓虹城市与故障美学 |
| 自然异变 | [`prompts/nature/`](./prompts/nature/) | 生物、植物与自然规律的超现实变形 |
| 日常错位 | [`prompts/daily/`](./prompts/daily/) | 熟悉物件与场景中的逻辑崩塌 |
| 宇宙漫游 | [`prompts/cosmos/`](./prompts/cosmos/) | 宇宙、虚空、尺度与维度错乱 |
| 古典重构 | [`prompts/classical/`](./prompts/classical/) | 古典意象的当代抽象演绎 |
| 混沌综合 | [`prompts/chaos/`](./prompts/chaos/) | 无法归类的跨题材混搭 |

### 奶龙系列

奶龙系列建议上传角色参考图，完整说明见 [奶龙使用指南](./prompts/nailong/README.md)。

| 子分类 | 目录 | 核心笑点 |
|---|---|---|
| 美食冲突 | [`cooking-fight/`](./prompts/nailong/cooking-fight/) | 抢饭引发的笨拙格斗 |
| 存在主义 | [`existential/`](./prompts/nailong/existential/) | 前 90% 严肃，最后 10% 犯病 |
| 时尚走秀 | [`fashion/`](./prompts/nailong/fashion/) | 高奢视觉与卡通物理失误 |
| 宇宙降临 | [`cosmic/`](./prompts/nailong/cosmic/) | 史诗末日被一份外卖瓦解 |
| 纪录片 | [`documentary/`](./prompts/nailong/documentary/) | 自然纪录片写实感与次元反差 |
| 一句话抽象 | [`crossover/`](./prompts/nailong/crossover/) | 一句话完成铺垫和反转 |

### 垃圾抽象系列

| 子分类 | 提示词 | 入口 |
|---|---:|---|
| 监控录像事故 | 10 | [`surveillance-failures.md`](./prompts/trashcore/surveillance-failures.md) |
| 五毛商业广告 | 10 | [`cheap-commercials.md`](./prompts/trashcore/cheap-commercials.md) |
| 乡镇舞台奇观 | 10 | [`county-stage.md`](./prompts/trashcore/county-stage.md) |
| 职场系统失控 | 10 | [`office-malfunctions.md`](./prompts/trashcore/office-malfunctions.md) |
| 食物邪典现场 | 10 | [`food-abominations.md`](./prompts/trashcore/food-abominations.md) |
| 公共空间迷惑行为 | 10 | [`public-space-nonsense.md`](./prompts/trashcore/public-space-nonsense.md) |

## 精选提示词

### 时间戳下班

```text
空仓库监控画面，场景完全静止，只有右上角时间戳突然从屏幕上掉下来，
像实体数字一样摔在地上。清洁工进来扫走数字，画面从此停在 18:00:00。
```

`trashcore` · `监控` · `低清` · [查看合集](./prompts/trashcore/surveillance-failures.md)

### 赛博城市溶解

```text
一座超高密度赛博朋克城市在看不见的太阳下像蜡一样缓慢融化，
霓虹招牌滴落成光河，行人对此毫无察觉。街道向上折叠成莫比乌斯环，
镜头持续向前漂移，穿过循环往复的不可能几何空间。
```

`cyber` · `城市` · `循环` · [查看完整提示词](./prompts/cyber/melting-city.md)

### 奶龙：最后的希望

```text
世界末日后的上海，一个巨型奶龙从云层缓缓降落，全球媒体直播，军队严阵以待。
奶龙落在城市中央，所有人屏住呼吸。
它低头，从肚子后面掏出一份外卖，坐在废墟上开始吃饭。
```

`nailong/cosmic` · `需要参考图` · [查看完整提示词](./prompts/nailong/cosmic/last-hope.md)

## 工具兼容性

提示词没有绑定特定模型。实际效果取决于模型版本、生成时长、参考图和随机种子。

| 工具 | 适合场景 | 角色参考 |
|---|---|---|
| Seedance 2.0 / 即梦 | 中文理解、复杂运动与短视频节奏 | 支持 |
| Kling / 可灵 | 主体一致性与真实运动 | 支持 |
| Vidu | 角色稳定与参考图工作流 | 支持 |
| Sora | 开放式概念与空间变化 | 视版本而定 |
| Runway | 镜头控制与电影质感 | 视版本而定 |

> 仓库中的“推荐工具”表示作者认为适合，并不代表每条提示词都经过所有平台的系统测试。

## 仓库结构

```text
awesome-subspace/
├── prompts/
│   ├── nailong/       # 角色 Meme 系列
│   ├── trashcore/     # 60 条垃圾抽象提示词
│   ├── cyber/         # 赛博抽象
│   ├── nature/        # 自然异变
│   ├── daily/         # 日常错位
│   ├── cosmos/        # 宇宙漫游
│   ├── classical/     # 古典重构
│   ├── chaos/         # 混沌综合
│   └── TEMPLATE.md    # 投稿模板
├── CONTRIBUTING.md
├── README.md
└── README.zh-CN.md
```

## 贡献

欢迎原创提示词、现有提示词优化、新分类和真实生成反馈。

1. Fork 仓库并创建分支。
2. 在对应分类中新建 Markdown 文件。
3. 按照 [提示词模板](./prompts/TEMPLATE.md) 填写内容。
4. 提交 Pull Request，并说明测试工具与预期效果。

开始前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

### 质量标准

- 至少包含一个违反物理规律或日常逻辑的元素。
- 描述可见的运动、变化或镜头过程。
- 保持可执行，避免只堆叠风格关键词。
- 内容须为原创或明确注明来源。
- 不包含违法、色情、歧视或伤害性内容。

## 社区

- 发现问题或有分类建议，请提交 [Issue](https://github.com/awesome-subspace/awesome-subspace/issues)。
- 想补充或改进提示词，请直接提交 [Pull Request](https://github.com/awesome-subspace/awesome-subspace/pulls)。

---

<div align="center">

**如果这个仓库给了你一点荒诞灵感，欢迎 Star。**

由 `awesome-subspace` 社区维护。

</div>
