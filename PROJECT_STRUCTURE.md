# PROJECT_STRUCTURE

## 根目录

- `README.md`: 仓库说明、目录导航和推荐使用路径。
- `WORKFLOW_GUIDE.md`: 三个方向工作流说明的总导航。
- `PROJECT_STRUCTURE.md`: 当前仓库结构说明和维护约定。
- `SOURCE.md`: 来源与改编说明。
- `01-product-decision-chain/`: 产品决策链 Skills。
- `03-learning-and-research/`: 学习、研究、产品拆解相关 Skills。
- `04-knowledge-and-writing/`: 知识沉淀与文章共创相关 Skills。

## 分类规则

### 01-product-decision-chain

放置从想法、用户痛点、商业判断、市场需求到 PRD/项目规范的 Skills。

当前包含：

- `WORKFLOW_GUIDE.md`
- `product-insight-miner`
- `brd`
- `mrd`
- `vibe-prd-writer`
- `ai-agent-prd-writer`

### 03-learning-and-research

放置领域学习、产品拆解、竞品研究相关 Skills。

当前包含：

- `WORKFLOW_GUIDE.md`
- `ai-product-teardown`
- `48h-accelerated-learning`
- `interactive-learning`

### 04-knowledge-and-writing

放置知识库沉淀和文章写作相关 Skills。

当前包含：

- `WORKFLOW_GUIDE.md`
- `obsidian-knowledge-saver`
- `simin-article-cowriter`

## 明确排除

本仓库不包含 AI 产品经理求职方向内容：

- 不包含简历优化 Skill。
- 不包含面试诊断 Skill。
- 不包含 JD 研究、面试复盘、简历文档等过程产物。

## 维护约定

- 新增 Skill 时，优先按实际使用场景归入现有分类。
- 保留每个 Skill 的完整目录结构，不拆散 `references/`、`scripts/`、`templates/`。
- 更新上游内容时，先记录来源 commit，再替换对应 Skill 目录。
- 修改分类后，同步更新 `README.md` 和本文件。
