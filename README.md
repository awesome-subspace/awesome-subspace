<div align="center">

# awesome-subspace

**A curated collection of surreal prompts for AI-generated video.**

[![Stars](https://img.shields.io/github/stars/awesome-subspace/awesome-subspace?style=flat-square&logo=github&label=Stars)](https://github.com/awesome-subspace/awesome-subspace/stargazers)
[![Forks](https://img.shields.io/github/forks/awesome-subspace/awesome-subspace?style=flat-square&logo=github&label=Forks)](https://github.com/awesome-subspace/awesome-subspace/forks)
[![Contributors](https://img.shields.io/github/contributors/awesome-subspace/awesome-subspace?style=flat-square&label=Contributors)](https://github.com/awesome-subspace/awesome-subspace/graphs/contributors)
[![Last Commit](https://img.shields.io/github/last-commit/awesome-subspace/awesome-subspace?style=flat-square&label=Last%20commit)](https://github.com/awesome-subspace/awesome-subspace/commits/main)
[![Prompts](https://img.shields.io/badge/curated_prompts-60%2B-2ea44f?style=flat-square)](./prompts/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-2ea44f?style=flat-square)](CONTRIBUTING.md)

English | [简体中文](README.zh-CN.md)

[Browse prompts](./prompts/) · [Contributing](CONTRIBUTING.md) · [Prompt template](./prompts/TEMPLATE.md)

</div>

---

## About

`awesome-subspace` is a curated prompt library for surreal AI video generation. Instead of stacking random style keywords, each prompt combines a clear subject, impossible motion, practical camera direction, and a deliberate visual payoff.

Built for:

- Text-to-video and image-to-video experiments
- Memes, absurd shorts, and visual concept studies
- Seedance, Kling, Vidu, Sora, Runway, and other video models
- Chinese and English prompts, including reference-image workflows

## Quick Start

1. Pick a collection from the directory below.
2. Open a prompt file and copy a code block.
3. Paste it into your video model and add duration, aspect ratio, or camera controls as needed.
4. Got a strong result? Contribute your prompt or variation.

```text
Subject
+ Impossible event
+ Visible motion
+ Camera and texture
+ Final payoff
```

> Tip: If the model makes everything too polished, explicitly request CCTV framing, cheap phone footage, unstable auto-exposure, harsh lighting, or no cinematic look.

## Collections

| Collection | Path | Focus |
|---|---|---|
| Nailong | [`prompts/nailong/`](./prompts/nailong/) | Character memes with deadpan setups and ridiculous endings; reference image required |
| Trashcore | [`prompts/trashcore/`](./prompts/trashcore/) | 60 lo-fi prompts with cheap effects, awkward performances, and pointless twists |
| Cyber | [`prompts/cyber/`](./prompts/cyber/) | Digital spaces, neon cities, and glitch aesthetics |
| Nature | [`prompts/nature/`](./prompts/nature/) | Surreal mutations of living systems and natural laws |
| Daily | [`prompts/daily/`](./prompts/daily/) | Familiar objects and places behaving impossibly |
| Cosmos | [`prompts/cosmos/`](./prompts/cosmos/) | Space, voids, scale shifts, and dimensional anomalies |
| Classical | [`prompts/classical/`](./prompts/classical/) | Contemporary surreal takes on classical imagery |
| Chaos | [`prompts/chaos/`](./prompts/chaos/) | Cross-genre concepts that resist classification |

### Nailong Series

The Nailong series works best with a character reference image. See the [Nailong guide](./prompts/nailong/README.md) for setup details.

| Series | Path | Core gag |
|---|---|---|
| Cooking Fight | [`cooking-fight/`](./prompts/nailong/cooking-fight/) | Clumsy fights over food |
| Existential | [`existential/`](./prompts/nailong/existential/) | A serious setup followed by a ridiculous ending |
| Fashion | [`fashion/`](./prompts/nailong/fashion/) | Luxury visuals versus cartoon physics |
| Cosmic | [`cosmic/`](./prompts/nailong/cosmic/) | Epic doom interrupted by takeaway food |
| Documentary | [`documentary/`](./prompts/nailong/documentary/) | Nature-documentary realism with a dimensional mismatch |
| One-liners | [`crossover/`](./prompts/nailong/crossover/) | Setup and payoff in one sentence |

### Trashcore Series

| Series | Prompts | Path |
|---|---:|---|
| Surveillance Failures | 10 | [`surveillance-failures.md`](./prompts/trashcore/surveillance-failures.md) |
| Cheap Commercials | 10 | [`cheap-commercials.md`](./prompts/trashcore/cheap-commercials.md) |
| County Stage | 10 | [`county-stage.md`](./prompts/trashcore/county-stage.md) |
| Office Malfunctions | 10 | [`office-malfunctions.md`](./prompts/trashcore/office-malfunctions.md) |
| Food Abominations | 10 | [`food-abominations.md`](./prompts/trashcore/food-abominations.md) |
| Public-space Nonsense | 10 | [`public-space-nonsense.md`](./prompts/trashcore/public-space-nonsense.md) |

## Featured Prompts

### The Timestamp Clocks Out

```text
Empty warehouse CCTV footage. The scene is completely still until the timestamp
in the upper-right corner falls out of the screen like a physical object.
A cleaner sweeps the digits away. The footage remains frozen at 18:00:00 forever.
```

`trashcore` · `CCTV` · `lo-fi` · [Open collection](./prompts/trashcore/surveillance-failures.md)

### Melting Cyber City

```text
A hyper-dense cyberpunk city slowly melts like wax under an invisible sun,
neon signs dripping into rivers of light, pedestrians unaware as the streets
fold upward into a Mobius strip, looping forever, camera drifting forward
through the impossible geometry, glitchy ambient soundtrack.
```

`cyber` · `city` · `loop` · [Open prompt](./prompts/cyber/melting-city.md)

### Nailong: The Last Hope

```text
Post-apocalyptic Shanghai. A giant Nailong slowly descends through the clouds
as global media broadcast live and the military holds position. It lands in the
city center, pulls out a takeaway meal, sits in the ruins, and starts eating.
```

`nailong/cosmic` · `reference required` · [Open prompt](./prompts/nailong/cosmic/last-hope.md)

## Model Compatibility

Prompts are model-agnostic. Results vary by model version, duration, reference image, and seed.

| Model | Strength | Character reference |
|---|---|---|
| Seedance 2.0 | Chinese prompts, complex motion, and short-form pacing | Yes |
| Kling | Subject consistency and realistic motion | Yes |
| Vidu | Stable characters and reference-image workflows | Yes |
| Sora | Open-ended concepts and spatial transformations | Version-dependent |
| Runway | Camera control and cinematic output | Version-dependent |

> A recommended model is an author suggestion, not a claim that every prompt has been systematically benchmarked on every platform.

## Repository Structure

```text
awesome-subspace/
├── prompts/
│   ├── nailong/       # Character meme series
│   ├── trashcore/     # 60 lo-fi absurdist prompts
│   ├── cyber/         # Cyber surrealism
│   ├── nature/        # Mutated nature
│   ├── daily/         # Everyday absurdity
│   ├── cosmos/        # Cosmic concepts
│   ├── classical/     # Classical remixes
│   ├── chaos/         # Mixed chaos
│   └── TEMPLATE.md    # Contribution template
├── CONTRIBUTING.md
├── README.md
└── README.zh-CN.md
```

## Contributing

Original prompts, refinements, new collections, and generation feedback are welcome.

1. Fork the repository and create a branch.
2. Add a Markdown file to the appropriate collection.
3. Follow the [prompt template](./prompts/TEMPLATE.md).
4. Open a pull request with the model used and expected result.

Read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

### Quality Bar

- Include at least one impossible or illogical event.
- Describe visible motion, transformation, or camera behavior.
- Keep the prompt actionable instead of stacking style keywords.
- Submit original work or clearly credit the source.
- Do not include illegal, sexual, discriminatory, or harmful content.

## Community

- Found a problem or have a collection idea? Open an [issue](https://github.com/awesome-subspace/awesome-subspace/issues).
- Want to add or improve a prompt? Send a [pull request](https://github.com/awesome-subspace/awesome-subspace/pulls).

---

<div align="center">

**If this repository gave you one strange idea, consider leaving a star.**

Maintained by the `awesome-subspace` community.

</div>
