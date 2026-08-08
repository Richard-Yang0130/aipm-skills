# AIPM Skills

这是一个面向 AI 产品经理工作的 Skills 合集，聚焦产品决策、学习研究、知识沉淀和内容输出三类高频场景。

本仓库不包含 AI 产品经理求职方向内容，例如简历优化、面试诊断、JD 匹配等模块。

## 目录

- `01-product-decision-chain/`: 从用户痛点、商业判断、市场需求到 PRD/项目规范。
- `03-learning-and-research/`: 领域学习、产品拆解、竞品研究。
- `04-knowledge-and-writing/`: Obsidian 知识沉淀、长文共创与社交媒体视觉内容制作。
- `WORKFLOW_GUIDE.md`: 三个方向的总导航。
- `PROJECT_STRUCTURE.md`: 仓库结构说明。
- `SOURCE.md`: 来源与改编说明。

## 适用场景

### 从想法到产品

```text
product-insight-miner
  -> brd
  -> mrd
  -> vibe-prd-writer
  -> Claude Code / Cursor / Codex 开发
```

适合在产品想法还不清晰时，先采集用户声音，再判断方向是否值得做，最后生成可执行的 PRD 或项目规范。

### 能力建设与入职加速

```text
48h-accelerated-learning
  -> interactive-learning
  -> ai-product-teardown
```

适合快速进入陌生领域、建立知识地图、系统学习关键概念，并拆解 AI 产品或竞品。

### 知识沉淀与内容输出

```text
obsidian-knowledge-saver
  -> simin-article-cowriter
  -> obsidian-knowledge-saver
```

适合把学习、调研、产品拆解和项目复盘沉淀为 Obsidian 原子笔记，或进一步转化成可发布长文。

## 包含的 Skills

### 产品决策链

- `product-insight-miner`: 采集和整理用户痛点、产品洞察。
- `brd`: 判断方向是否值得做，形成商业需求判断。
- `mrd`: 梳理市场需求、优先级和目标用户。
- `vibe-prd-writer`: 生成面向 AI Agent 执行的项目规范。
- `ai-agent-prd-writer`: 生成工作场景中的正式 AI Agent PRD。

### 学习与研究

- `ai-product-teardown`: 拆解 AI 产品、竞品和目标公司产品。
- `48h-accelerated-learning`: 48 小时快速建立陌生领域认知框架。
- `interactive-learning`: 针对具体知识点进行交互式深入学习。

### 知识沉淀与写作

- `obsidian-knowledge-saver`: 将对话和知识点沉淀到 Obsidian 知识库。
- `simin-article-cowriter`: 辅助撰写 AI PM、AI 产品、Agent 等方向的长文。
- `social-visual-content-studio`: 将多模态素材转化为跨平台图文或短视频内容。

## 使用方式

复制需要的 Skill 文件夹到 Codex 或 Claude 的 Skills 目录。每个 Skill 需要保留完整文件夹结构，不要只复制 `SKILL.md`。

常见路径：

```text
~/.codex/skills/
~/.claude/skills/
```

复制后重启对应客户端，让新 Skill 生效。
