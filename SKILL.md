---
name: aipm-pro-review
description: Use when the user asks to review, package, tailor, or recall AI product manager project experiences, especially Ximalaya/心屿/AI companion/AIPM internship materials, resume bullets, STAR stories, Prompt Engineering, SFT/model-eval positioning, A/B experiments, or JD-matching for AI PM roles.
---

# AIPM-Pro Review

## Overview

This skill turns messy AI product/project materials into a fact-preserving, resume-ready AI Product Manager narrative. It is optimized for AI PM internship review, JD matching, STAR storytelling, and project-to-capability packaging.

Core principle: **package aggressively, fabricate nothing**. Reframe real work around AI PM capabilities, but do not invent model training, ownership, metrics, or outcomes that are not supported by source materials.

Story principle: **respect the original project, then expand from it**. A limited project can be packaged to reveal the broader knowledge system behind it, but the answer must clearly distinguish:

1. **Project facts**: what the project actually implemented, designed, tested, deployed, or documented.
2. **Product judgment**: why the user made certain product, architecture, priority, metric, or interaction choices.
3. **Knowledge extension**: how the same project connects to production-grade AI PM knowledge such as Agent architecture, workflow orchestration, memory, evaluation, observability, business funnels, privacy, and frontier technical routes.

Use this default sentence pattern when packaging small or demo projects:

> "In the original project, we used a demo / prototype to validate X; the product judgment I want to highlight is Y; if moving toward production, I would extend it with Z."

This lets the user show depth without pretending that a hackathon, class project, prototype, or early demo has already proven production-scale impact.

## When to Use

Use this skill when the user wants to:

- Rework an internship/project into AI Product Manager resume material.
- Recall the Ximalaya/心屿 AI product internship review.
- Generate STAR stories, interview talking points, or resume bullets.
- Match project evidence to AI PM JD keywords such as Agent, Workflow, Prompt Engineering, SFT, model evaluation, A/B experiments, AI evaluation tools, multimodal/AIGC, user research, or growth/product strategy.
- Convert “运营/文档/需求跟进” descriptions into product-system, experiment, and metric language.

When the user explicitly mentions Ximalaya, 心屿, 喜马拉雅 AI PM, or “上次复盘”, first read:

- `references/ximalaya-review-memory.md`

## Input Discovery

Before writing, identify what is available:

1. Target JD or target role:
   - AI Product Manager
   - Agent/Workflow PM
   - Model evaluation/Data PM
   - AIGC/Multimodal PM
   - Growth/Experiment PM
   - Commercialization PM
   - Content/community/AI companion PM
2. Source materials:
   - PRD files, Notion pages, Feishu folders, local docs, spreadsheets, old resume, interview diagnosis.
3. Evidence strength:
   - Directly supported by source
   - Inferred from source
   - Missing and should be marked as a gap

If the user asks for “latest JD/market trend”, browse current sources. If they only ask to reuse stored memory, use the local memory first.

## Packaging Framework

Always reconstruct the project from two angles.

### 1. Project Panorama

Create a table like:

| Project module | Product problem | Product actions | Source files | AI PM capability |
|---|---|---|---|---|

Use modules such as:

- Market and strategy
- Content/world-building
- Role creation and creator ecosystem
- AI conversation Agent workflow
- Memory/context system
- Model evaluation and Bad Case loop
- Data analysis and user insight
- Commercialization and transaction system
- Growth product and A/B experiment platform
- AIGC/multimodal content production
- Lifecycle and risk communication

### 2. Capability Repackaging

Recombine the same evidence for different target roles:

| Target JD | Lead project package | Resume-facing wording | Interview expansion |
|---|---|---|---|

Common packages:

- AI conversation Agent and long-term memory system
- AI dialogue quality evaluation and Bad Case loop
- Product-side SFT/model-tuning data loop
- Growth product A/B experiment system
- AIGC visual/content production workflow
- Commercialization and virtual currency system
- International/market research and content strategy

## STAR Rules

For each major experience, write:

- Situation: real product context and pain point.
- Task: product responsibility or problem to solve.
- Action: concrete product design, evaluation, data, workflow, or cross-functional work.
- Result: use supported numbers whenever possible.

Prefer supported output metrics over fabricated impact metrics:

- Good: “covered 74,179 rows of dialogue data”
- Good: “defined 5 evaluation dimensions”
- Good: “designed 3 A/B experiment directions”
- Risky: “improved retention by 20%” unless source proves it

## Interview Deep-Dive Pattern

When the user asks for interview answers or mock interview preparation, do not let answers become a chronological task list. Convert every project answer into a business-facing deep-dive. Interviewers often ask about the project not to hear what the candidate did step by step, but to test whether the candidate can reconstruct the business problem, define goals, prioritize, choose a solution from insight, and verify impact.

Use this six-part structure before or inside answers:

1. **Business problem / why now**
   - What problem was the business facing?
   - Which user behavior, product bottleneck, content supply issue, model quality issue, or conversion gap triggered the project?
   - Avoid saying only “the company needed this feature.”

2. **Core goal and metric**
   - Define the platform/business goal.
   - Define the user/product goal.
   - Define observable indicators: DAU, exposure-click, dialogue start, continuous turns, retention, shell/token consumption, payment conversion, task completion, OOC rate, bad-case rate, format pass rate, recall/false-recall rate.
   - Always explain what the metric means, not just name it.

3. **Decomposition and priority**
   - How was the problem decomposed?
   - Which sub-problem was solved first and why?
   - Common dimensions: user intent, content supply, model behavior, memory/context, workflow reliability, evaluation, commercialization path, risk/safety.
   - Explain priority by user impact, business impact, technical feasibility, and risk.

4. **Insight and solution choice**
   - What input led to the solution: user logs, paid-user behavior, competitive research, Bad Cases, product constraints, operational feedback, content strategy?
   - Why this solution was more effective than alternatives?
   - Name the tradeoff: automation vs human review, active trigger vs low-interruption clarification, long-context injection vs structured memory, direct conversion vs user experience.

5. **Build, optimize, and iterate**
   - Describe the Agent / Workflow as input -> node/process -> output -> fallback.
   - Include fields, schemas, prompts, tools, memory scopes, evaluation sets, and iteration loops.
   - Show how the solution changed across versions, not only the final version.

6. **Validation, data, and business link**
   - How was the effect verified: offline eval, human review, LLM-as-Judge, A/B test, log analysis, gray release, regression set?
   - What data was used and what did it look like: rows, columns, user logs, dialogue details, exposure/click/dialogue/retention/shell tables, paid-user dialogue-role records, annotation tables.
   - For content production or AI companion features, explain how better content can affect transaction conversion: exposure -> click -> dialogue start -> deep chat/scene trigger -> shell/token consumption -> payment or retention.

### Ximalaya / 心屿 Interview Narrative Anchor

For Ximalaya answers, make this the default project logic:

- **Business problem:** AI companion products rely on continuous immersive dialogue and high-value scene triggers, but 心屿 faced ambiguous user intent, unstable role dialogue quality, memory discontinuity, content safety review pressure, and a need to connect richer content scenes to retention/payment.
- **Platform goal:** improve AI character interaction quality and make “星梦/星事” scene content more triggerable, evaluable, and commercially meaningful.
- **User goal:** make the role feel like it understands me, remembers me, stays in character, and naturally invites me into deeper scenes without abrupt interruption.
- **Agent/workflow goal:** parse ambiguous short-dialogue intent, complete missing slots with low interruption, route to scene/content workflow, maintain memory context, and use evaluation/Bad Case loops for continuous improvement.
- **Business conversion logic:** better intent recognition and content supply do not directly equal payment, but they can increase scene entry, dialogue depth, shell/token consumption, paid-user engagement, and retention. Use this as a hypothesis unless hard conversion proof exists.
- **Data forms to mention:** 74,179 dialogue-detail rows; 247,755 exposure rows; 129,371 click rows; 59,777 dialogue rows; 3,886 retention rows; 2,650 shell rows; 230 paid-user rows; 921 paid-user dialogue-role rows; annotation tables and Bad Case sets.

### Difficulty / Setback Answer Pattern

When asked about setbacks, avoid generic “communication was hard.” Use:

1. Initial assumption.
2. What failed or contradicted the assumption.
3. Diagnosis using data / logs / user feedback / Bad Cases.
4. Adjustment to priority or solution.
5. What was learned about product judgment.

Good Ximalaya examples:

- More context did not always improve model quality because it introduced noise.
- More follow-up questions could improve field completeness but hurt user experience.
- More automated moderation could improve efficiency but still needed human review for boundary samples.
- Richer content scenes could support conversion, but only if trigger timing and user intent confidence were controlled.

### Product Taste / Favorite App Questions

When asked about a favorite app, answer with:

1. Target user and core job-to-be-done.
2. Best product point with a specific interaction detail.
3. Metric or behavioral reason why it works.
4. Biggest weakness.
5. How to improve without damaging the original experience.

### Commercialization vs User Experience

When asked how to balance commercialization and user experience, use:

1. Commercialization should monetize moments of high intent or high value, not interrupt low-intent usage.
2. Separate short-term conversion metrics from long-term retention/trust.
3. Use layered experiments: exposure -> click -> scene entry -> deep interaction -> shell consumption -> payment -> retention.
4. Protect user experience with frequency caps, confidence thresholds, preview/confirmation, fallback, and negative feedback monitoring.
5. For AI companion products, content-driven commercialization must first prove it increases immersion and dialogue depth; otherwise it becomes intrusive.

## Resume Bullet Format

Use `resume-builder` style:

```markdown
- **Capability summary:** Action + object + method + source-backed result/scale + role/JD keyword.
```

Every bullet should include:

- Capability tag: Agent, model evaluation, SFT data loop, Prompt Engineering, A/B experiment, data analysis, AIGC, commercialization.
- Product action: designed, defined, decomposed, organized, evaluated, analyzed, built the framework for.
- Evidence/data: rows, files, rules, dimensions, modules, sample pools, states, workflows.
- Business connection: retention, conversion, quality, content supply, user experience, model iteration, launch evaluation.

## Growth Product Rewrite

When a section sounds like operations, rewrite it as product experimentation:

- “做 Push 召回” -> “designed recall experiment variables and metrics”
- “首页配置运营位” -> “built configurable exposure layer for A/B entrance testing”
- “任务签到” -> “designed incentive mechanism with task-completion and retention metrics”

Use this structure:

1. User/product hypothesis
2. Product variable
3. Experiment group/control group idea
4. Metrics: exposure, click, dialogue start, retention, token/shell consumption, payment conversion
5. Decision loop: ship, rollback, iterate, segment

## Prompt Engineering Packaging

Package Prompt work as a product quality system, not just “wrote prompts”.

Look for:

- Thought template
- Output constraints
- Style constraints
- Negative examples
- Bad expression blacklist
- Regression examples
- Evaluation connection

Strong bullet pattern:

```markdown
- **Prompt Engineering:** Designed structured prompt rules for AI character dialogue, covering [template count] reasoning steps, [framework] interaction logic, output length/style constraints, negative examples, and Bad Case regression criteria, turning subjective response quality into evaluable dimensions.
```

## SFT / Model Tuning Positioning

Be careful. Unless the source proves actual training ownership, do not say the user “trained” or “fine-tuned” the model.

Use product-side SFT language:

- Defined tuning objectives
- Mined Bad Cases
- Designed annotation guidelines
- Selected high-value samples
- Built eval set/regression set
- Coordinated with algorithm/QA/annotation teams
- Defined offline and online acceptance metrics

Explain SFT to non-technical AI PM interviewers as:

1. Define the business behavior to improve.
2. Collect real user dialogues, Bad Cases, and high-quality responses.
3. Convert them into instruction or `system/user/assistant` samples.
4. Split train/eval/regression sets.
5. Coordinate training with algorithm engineers.
6. Validate through offline eval, human review, and online A/B.

When strengthening fine-tuning positioning, use this boundary:

- CoT/few-shot/Prompt Engineering are not fine-tuning, but they can prove the user can define the model behavior that SFT should learn.
- Convert thought templates into ideal-answer structure and evaluation dimensions.
- Convert few-shot positive/negative examples into SFT demonstration samples and regression cases.
- Convert bad-expression blacklists into annotation rules and negative labels.
- Convert Bad Case analysis into sample mining, training priorities, and version regression.
- For LoRA/QLoRA, frame as process understanding or interview scenario unless actual training logs/model versions exist.

For Ximalaya/心屿, fine-tuning package should include:

- SFT standards: role consistency, intent satisfaction, plot continuity, emotional response, safety boundary, no invented setting, no repeated expression, format compliance.
- Sample pool: 74,179 dialogue-detail rows, 230 paid-user rows, 921 paid-user dialogue-role rows, dialogue tags, QA/mechanical test cases, Prompt bad cases.
- Product-side deliverables: sample admission rules, label taxonomy, `system/user/assistant` formatting assumptions, train/eval/regression split, offline eval, human blind review, online A/B and rollback criteria.

## Big-Tech Interviewer Lens

When reviewing or packaging a project for AI PM interviews, first generate a hidden or explicit interviewer-question map. Use it to decide which hooks to plant in the story. Do not wait for the user to ask for mock questions if the task is project review, interview preparation, or storytelling.

When generating big-tech-style questions, also generate project-specific mock answers by default unless the user explicitly asks for questions only. The answers must imitate the target company's questioning style, but stay grounded in the project.

Mock-answer rules:

1. Start with a direct conclusion, then expand with project evidence.
2. Use the three-layer storytelling structure: project facts -> product judgment -> knowledge extension.
3. Adjust the answer style to the company lens:
   - Tencent / WXG: restraint, scenario fit, trust, privacy, product taste, "what not to build".
   - ByteDance: metric tree, funnel, baseline, A/B, bad cases, latency / cost / quality tradeoff.
   - Alibaba: business chain, supply-demand matching, transaction linkage, stakeholder collaboration, ROI.
   - Xiaohongshu: real user scene, UGC trust, community ecology, subjective taste, commercialization restraint.
4. Include one "interviewer hook" in answers where useful, so the interviewer is naturally invited to ask about Agent boundary, Memory, evaluation, observability, business funnel, or productionization.
5. Do not invent unsupported metrics. If the answer needs data that the project does not have, say how to validate it instead.
6. For each answer, prefer a structure like:

```markdown
**短答：** ...

**展开：** ...

**如果继续追问：** ...
```

### WXG / Tencent Product Lens

Tencent / WXG-style interviewers often test whether the candidate can think from restraint, scenario fit, trust, and product taste rather than just feature expansion.

Common question angles:

1. What is the real user problem, not the feature description?
2. Why should this product solve it now?
3. Why is this not just a bigger AI entry point or feature pile?
4. Which scenario should AI appear in, and when should it quietly leave?
5. What is the smallest MVP that proves the value?
6. How do you avoid interrupting users with clarification or recommendations?
7. What is the trust mechanism: citation, source trace, controllability, privacy, reversibility?
8. How do you judge product taste beyond metric optimization?
9. Which user behavior proves the feature is naturally useful?
10. What would you deliberately not do?
11. How do you balance user experience and commercialization?
12. What is the failure mode if the AI is too proactive?
13. How do you handle privacy, sensitive scenes, and user mental models?
14. How do you design evaluation so it respects content or language quality?
15. How would this connect to the broader ecosystem without becoming intrusive?
16. If the team disagrees, what data or small experiment would you use?
17. What is the biggest gap between your previous experience and this product?
18. How would you spend the first 3 weeks after joining the team?
19. What would you ask the interviewer that proves you studied the product?
20. What is the most important tradeoff you made, and what did it cost?

Storytelling habit:

- Plant hooks around "restraint", "trust", "minimal viable proof", "do-not-do list", "privacy / memory boundary", and "AI appears only when it solves a concrete scenario".
- For language/content products, emphasize quality, source grounding, expression nuance, and low-interruption interaction.

### ByteDance Product Lens

ByteDance-style interviews tend to pressure-test logical density, product sense, data awareness, execution speed, and whether the candidate can connect AI capability to growth or content distribution. Public interview experiences on 牛客 and 小红书 commonly emphasize project deep-dives, product sense cases, data analysis, ownership, and AI / recommendation / content ecosystem questions. Treat these as style references, not official company rules.

Common question angles:

1. What is the core metric, and why this metric?
2. What is the north-star metric versus the guardrail metric?
3. How would you decompose the funnel?
4. Which user segment would you start with?
5. What is the opportunity size or frequency?
6. How did you prioritize when resources were limited?
7. What did you learn from logs, queries, click behavior, or retention?
8. How would you design an A/B test?
9. What is the baseline, experiment group, and rollback condition?
10. How do you distinguish product failure from model failure?
11. Why Agent / Workflow rather than a deterministic product flow?
12. Where should rules beat the model?
13. How do you control latency, cost, and quality?
14. What are the top 3 bad cases?
15. How would you build a regression set?
16. If the product suddenly scales 10x, what breaks first?
17. What is the user growth or distribution mechanism?
18. What would you cut from the first version?
19. What would be your 30-day iteration plan?
20. If data contradicts your intuition, what would you do?

Storytelling habit:

- Plant hooks around "metric tree", "baseline", "funnel", "A/B or offline eval", "bad-case loop", "latency / cost / quality tradeoff", and "fast iteration".
- Translate Agent design into measurable product behavior: query -> intent success -> candidate quality -> confirmation -> downstream action -> retention or reuse.

### Alibaba Product Lens

Alibaba-style interviews often lean toward business model, platform efficiency, transaction linkage, customer / merchant value, collaboration, and structured STAR review. Public interview experiences on 牛客 and 小红书 commonly mention business understanding, project ownership, commercial thinking, scenario design, and cross-functional tradeoffs. Treat these as style references, not official company rules.

Common question angles:

1. Which business problem did this project serve?
2. Who are the supply-side and demand-side users?
3. What is the transaction or fulfillment link?
4. How does the product improve efficiency, conversion, or trust?
5. What is the platform value, not just user experience value?
6. What are the key stakeholders and their conflicts?
7. How did you coordinate algorithm, engineering, operations, design, or BD?
8. What was your personal ownership boundary?
9. What business metric can this influence indirectly?
10. What is the cost of the solution?
11. What did you choose not to build because ROI was weak?
12. How would you commercialize without damaging experience?
13. How does the solution change supply quality or demand matching?
14. What is the data asset that accumulates over time?
15. What is the governance / risk / compliance boundary?
16. How would this become a reusable platform capability?
17. How would you convince a skeptical business owner?
18. What is the rollout plan from MVP to gray release?
19. What result is proven, inferred, or still a hypothesis?
20. If you redid the project, how would you improve business closed-loop?

Storytelling habit:

- Plant hooks around "demand-supply matching", "transaction path", "platform efficiency", "stakeholder tradeoff", "ROI", "gray release", and "data asset accumulation".
- Avoid claiming revenue impact without proof. Say "can influence X layer of the funnel" when the evidence is indirect.

### Xiaohongshu / Community Product Lens

Use this lens when the project touches UGC, travel / lifestyle decisions, content recommendation, community, or commercialization. Xiaohongshu-style questioning often values real user scenes, content ecology, trust, creator / consumer incentives, and the balance between utility and community atmosphere.

Common question angles:

1. What real-life scene triggers the need?
2. What content or community behavior already exists?
3. How does the feature preserve authenticity?
4. How do users judge whether a recommendation is trustworthy?
5. What role do UGC, reviews, notes, or creator supply play?
6. How do you avoid over-commercialized recommendations?
7. What is the difference between inspiration, decision, and transaction?
8. How do you design for browsing users versus high-intent users?
9. How would you measure content quality beyond clicks?
10. How do you handle subjective taste?
11. What is the cold-start strategy?
12. What is the negative feedback loop?

## Storytelling Timeboxes

For every major project, prepare four versions. Each version should plant deliberate hooks: the parts the user most wants the interviewer to ask about, and the parts that best prove AI PM depth.

### 3-Minute Version: Hooked Fast Pitch

Goal: make the interviewer remember the project and choose the right follow-up question.

Structure:

1. One-sentence product definition.
2. Real user / business problem.
3. Why the old solution was insufficient.
4. Your core product judgment.
5. System or workflow in 3-5 nodes.
6. One technical / Agent hook.
7. One metric / evaluation hook.
8. One reflective sentence: what you would improve.

Hook examples:

- "The key decision was not how many Agents to build, but which decisions should not be left to the model."
- "The hardest part was memory not becoming pollution."
- "I treated route generation as a constrained decision system, not content generation."

### 5-Minute Version: Focused STAR

Goal: show ownership and judgment without becoming a chronology.

Structure:

1. Situation: business and user context.
2. Task: your ownership and success criteria.
3. Action: 3 prioritized actions, each tied to a product judgment.
4. Result: proven outputs, supported data, demo state, or evaluation method.
5. Reflection: one limitation and one next iteration.

Rules:

- Use STAR, but do not give equal weight to every letter. Put most detail into Action and product judgment.
- Mention tradeoffs explicitly: speed vs quality, proactive vs interruption, memory vs privacy, Agent flexibility vs workflow controllability.
- If result metrics are not proven, say "we verified the chain / demo / eval design" rather than inventing conversion.

### 10-Minute Version: Full Product Chain

Goal: withstand continuous follow-up.

Structure:

1. Business problem and why now.
2. User segment and core scenario.
3. Platform / supply-side / business value.
4. Product goal and metric tree.
5. End-to-end chain: input -> process -> output -> feedback.
6. Agent / Workflow boundary.
7. Data structures, schemas, tools, and state.
8. Evaluation system and Bad Case loop.
9. Risk, fallback, privacy, and governance.
10. What to build next.

### 15-Minute Version: Technical Route + Product Thinking + Frontier Expansion

Goal: prove senior AI PM depth and show that the candidate can reason beyond the demo.

Structure:

1. Product strategy: why this problem matters and where it sits in the business.
2. Technical route: model, workflow, tools, memory, retrieval, guardrails, latency / cost choices.
3. Data route: logs, labels, eval sets, regression sets, online metrics.
4. Agent design: planner, executor, evaluator, monitor, fallback, and human confirmation.
5. Memory design: scope, confidence, decay, conflict, retrieval, and contamination prevention.
6. Frontend / interaction route: how users see progress, choose, correct, and trust the result.
7. Business link: exposure, confirmation, click, transaction / retention hypothesis.
8. Frontier expansion: multimodal input, real-time context, long-term personalization, tool ecosystem, MCP / external APIs, local privacy.
9. Limitations: what is not production-ready.
10. Next 30 / 60 / 90 day plan.

## Active Hook Injection

When producing project narratives, add hooks in the answer itself. A hook is a short sentence that invites the interviewer to ask about a high-value area.

Good hooks:

- "这里我最想强调的是，Agent 边界不是按功能名切，而是按不确定性和可验证性切。"
- "Memory 在这个项目里不是炫技点，反而是风险点，因为记错比不记更伤信任。"
- "这个结果我不会直接包装成 GMV 提升，我会把它放在路线确认和 POI 有效曝光这一层。"
- "如果面试官追问技术路线，我会重点讲 schema、工具调用和 Deny-first 过滤。"

Avoid:

- Empty hooks such as "这个项目很有挑战".
- Hooks that imply unsupported metrics or production scale.
- Hooks that invite questions the user cannot answer with evidence.

## Advanced Growth Track

When the user asks for a project review that should support interview growth, promotion preparation, or long-term AI PM development, add an "进阶成长路线" section. It should have three layers.

### 1. Foundation Knowledge Map

Summarize the project-related basic knowledge the user should master. This can come from local project materials, general LLM knowledge, official docs, or web research when freshness matters.

For AI Agent projects, include relevant items such as:

- LLM basics: token, context window, temperature, hallucination, tool calling, structured output.
- Agent architecture: planner, executor, evaluator, memory, monitor, fallback, human confirmation.
- Workflow architecture: deterministic nodes, schema validation, state machine, event stream, retries.
- RAG / retrieval: embedding, vector search, hybrid search, reranking, grounding, citation / source trace.
- Memory: session memory, atomic memory, scenario preference, persona, confidence, decay, conflict resolution.
- Evaluation: offline eval, regression set, LLM-as-Judge, rule-based checks, human review, online metrics.
- Product metrics: funnel, north-star metric, guardrail metric, latency, cost, quality, confirmation, retention.
- Safety / governance: privacy, sensitive data, refusal / fallback, audit log, controllability.

### 2. Frontier Insight Feed

Collect recent and relevant signals from public sources. Browse when the user asks for "latest", "前沿", "动态", or when the field is fast-moving.

Use a mix of:

- Official labs / platforms: OpenAI, Anthropic, Google DeepMind, Microsoft, Meta, Vercel, LangChain, LlamaIndex.
- Engineering blogs / docs: model eval, tool calling, agents, memory, deployment, observability.
- Newsletters: The Batch, Latent Space, Ben's Bites, TLDR AI, Import AI, Sequoia AI Ascent / AI notes.
- Podcasts: Latent Space, No Priors, The Cognitive Revolution, Practical AI, a16z Podcast, 20VC AI episodes.
- Chinese sources when relevant: 机器之心, Founder Park / 甲子光年 / 硅星人 / 晚点, 人人都是产品经理, AI 产品榜 / AI 科技评论, public WeChat articles if accessible.

For every trend, write:

1. What changed.
2. Why it matters to AI PM.
3. How it maps to this project.
4. What interview hook it creates.

Do not pretend newsletter or podcast claims are official facts. Label them as "industry signal", "practitioner discussion", or "opinion".

### 3. Practical Advancement Projects

Map project knowledge points to hands-on repositories, preferably top-starred or widely adopted GitHub projects. Use GitHub API or web search for current star counts when the user asks for top projects.

For each recommended project, include:

- Repository link and approximate stars / adoption signal.
- What to learn from it.
- Which part of the reviewed project it strengthens.
- A concrete 1-2 week practice task.

Common categories:

- Agent framework: LangChain, LangGraph, AutoGen, CrewAI, OpenAI Agents SDK examples.
- RAG / memory: LlamaIndex, Haystack, Qdrant, Chroma, Mem0, Letta.
- Evaluation / observability: Ragas, DeepEval, Phoenix, Langfuse, OpenTelemetry examples.
- Tool / workflow: FastAPI, Vercel AI SDK, Temporal, Prefect, Dify, n8n.
- Frontend / product demo: Next.js, Vercel AI Chatbot, Streamlit, Gradio.

Keep the recommendations tied to the project. Do not list generic repositories without explaining the practice path.

## Fact-Preservation Rules

- Do not invent growth rates, model accuracy, or revenue.
- If only sample scale is known, use sample scale.
- If only PRD scope is known, use “defined/designed/covered”.
- If the user’s role is unclear, use “参与/协同/负责整理/参与设计” instead of “主导”.
- Mark missing proof as “待补证据”.

## Output Sections

For a full review, produce:

1. Source scope and evidence boundary
2. Project panorama table
3. End-to-end project story
4. STAR stories by module
5. Resume bullets with output data
6. JD capability mapping
7. Gap repair plan
8. Interview opening pitch
9. Follow-up evidence needed

For a resume-only request, produce:

1. Target JD keywords
2. Best project packages
3. 3-6 resume bullets
4. Interview backup stories
5. Claims to avoid
