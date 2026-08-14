# 贡献指南

感谢你愿意为 awesome-subspace 贡献抽象提示词！

## 贡献流程

### 1. Fork & Clone

```bash
git clone https://github.com/<你的用户名>/awesome-subspace.git
cd awesome-subspace
```

### 2. 选择分类

在 `prompts/` 目录下选择合适的分类文件夹：

| 文件夹 | 适合内容 |
|--------|----------|
| `cyber/` | 赛博朋克、数字空间、科技感场景 |
| `nature/` | 自然元素的变形、生物奇观 |
| `daily/` | 日常物件与场景的荒诞化处理 |
| `cosmos/` | 宇宙、星际、维度、虚空 |
| `classical/` | 古风、古典意象的现代抽象演绎 |
| `chaos/` | 跨类别混搭、极限混沌 |

不确定分类？放进 `chaos/` 就对了。

### 3. 创建提示词文件

在对应目录下新建 `.md` 文件，文件名使用小写字母和连字符，简洁描述主题，例如：

```
prompts/cyber/melting-city.md
prompts/nature/fish-calligraphy.md
prompts/daily/chair-monologue.md
```

### 4. 按模板填写

复制 [`prompts/TEMPLATE.md`](./prompts/TEMPLATE.md) 的格式，填写你的提示词。

### 5. 提交 Pull Request

```bash
git add prompts/<分类>/<你的文件>.md
git commit -m "feat: add <简短描述> prompt"
git push origin main
```

然后在 GitHub 上开一个 Pull Request，简单描述你的提示词能生成什么效果即可。

---

## 提示词质量标准

**好的抽象提示词应该：**
- 包含至少一个违反物理规律或日常逻辑的元素
- 描述清晰的视觉运动或变化过程
- 画面感强，能让人脑补出画面
- 长度建议 50–300 字（英文）或 30–200 字（中文）

**我们不接受：**
- 违法、暴力、色情、歧视性内容
- 纯粹的写实场景描述（不够抽象）
- 直接复制他人作品而不注明来源
- 与 AI 视频生成无关的内容

---

## 格式规范

- 中英文提示词均欢迎，双语最佳
- 标签使用中文，简洁描述核心意象
- 文件名和目录名使用英文小写 + 连字符

---

## 有问题？

开一个 [Issue](https://github.com/awesome-subspace/awesome-subspace/issues) 或者直接在 PR 里说明。
