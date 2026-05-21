# AIPM-Pro Review Skill

AIPM-Pro Review 是一个面向 AI 产品经理求职、简历优化和面试复盘的 Agent Skill。它帮助用户把零散的实习、项目、运营、市场、内容、数据、设计、研究、工程或 QA 经历，重构成更适配 AI Product Manager 岗位的项目故事、STAR 案例、简历 bullet 和面试表达。

核心原则：**积极包装，但不编造事实。**

## 适用场景

- AI 产品经理简历优化
- AI PM 面试项目复盘
- 非产品背景转 AI 产品经理
- 运营、市场、内容、数据、设计、研究、工程、QA 等经历转产品叙事
- Agent、Workflow、Prompt Engineering、模型评测、SFT/LoRA、A/B 实验、AIGC、多模态、RAG/Memory 等能力包装
- 为不同 JD 生成定制化项目表述

## 它能输出什么

- 项目全景表
- STAR 项目故事
- AI PM 能力映射
- 可直接放进简历的 bullet
- 面试追问回答
- SFT/LoRA/Prompt-to-SFT 解释口径
- 不同职业转 AI PM 的互通点分析
- 不能夸大的风险声明

## 安装方式

把整个文件夹复制到你的 Codex / Claude / Agent skills 目录中，例如：

```bash
cp -R aipm-pro-review-skill ~/.codex/skills/aipm-pro-review
```

或只复制 `SKILL.md` 到对应 skill 目录：

```bash
mkdir -p ~/.codex/skills/aipm-pro-review
cp SKILL.md ~/.codex/skills/aipm-pro-review/SKILL.md
```

重启或刷新 Agent 后，可以用类似提示词触发：

```text
调用 AIPM-Pro Review，帮我把这段运营经历包装成 AI 产品经理简历项目。
```

## 推荐输入材料

- 目标岗位 JD
- 旧简历
- 项目 PRD / 复盘文档
- 数据表、看板截图、实验结果
- 用户研究、访谈、竞品分析
- Prompt、评测表、Bad Case 记录
- 会议纪要、上线记录、协作记录

## 职业转 AI 产品经理的包装方向

| 原背景 | 可迁移到 AI PM 的能力 | 包装重点 |
|---|---|---|
| 市场 | 用户洞察、定位、GTM、漏斗实验 | 把市场分析转为 AI 场景假设和产品定位 |
| 运营 | 流程设计、生命周期、指标拆解、实验执行 | 把运营动作转为产品机制和 A/B 变量 |
| 内容/社区 | 内容质量、创作者生态、审核标准 | 转为 AIGC 内容质量体系和创作者工具 |
| 数据分析 | 指标树、实验分析、评测体系 | 转为模型评测、数据产品和决策闭环 |
| UX/设计 | 用户旅程、交互、原型、可用性测试 | 转为 AI 交互流程和异常状态设计 |
| 研究/战略 | 需求发现、竞品、机会判断 | 转为 AI 场景发现和产品路线图 |
| 工程/QA | 系统思维、测试、质量控制 | 转为 Agent Workflow、模型评测和上线验收 |
| 销售/客户成功 | 场景发现、解决方案、ROI | 转为 AI 解决方案产品和落地路径 |

## 示例提示词

```text
我做过市场增长和用户调研，想转 AI 产品经理。请调用 AIPM-Pro Review，把我的经历重构成 3 条 AI PM 简历 bullet 和 2 个 STAR 面试故事。
```

```text
这段项目里我没有亲自训练模型，但做过 Prompt、Bad Case 和评测。请帮我包装成产品侧 SFT 数据闭环，不要夸大。
```

```text
请把我的运营项目改写成 AI 产品经理视角，重点突出 A/B 实验、指标体系、用户分层和产品机制。
```

## 发布到 GitHub

1. 在 GitHub 创建一个新仓库，例如 `aipm-pro-review-skill`。
2. 在本地进入本文件夹：

```bash
cd ~/Desktop/aipm-pro-review-skill
```

3. 初始化并提交：

```bash
git init
git add .
git commit -m "feat: add aipm pro review skill"
```

4. 连接远程仓库并推送：

```bash
git branch -M main
git remote add origin https://github.com/YOUR_NAME/aipm-pro-review-skill.git
git push -u origin main
```

5. 如果希望别人安装，README 中保留复制到 `~/.codex/skills/` 的安装说明即可。

## 隐私提醒

发布前请检查：

- 是否包含真实公司内部文件名
- 是否包含真实用户数据
- 是否包含私有项目链接
- 是否包含未经授权的业务指标
- 是否包含个人联系方式或简历隐私

本仓库当前版本已去除个人项目和私有数据，仅保留通用方法论。
