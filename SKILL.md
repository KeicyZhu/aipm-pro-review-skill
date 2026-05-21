---
name: aipm-pro-review
description: Use when a user wants to package existing work, internships, projects, or career-transition experience for AI Product Manager roles, especially when the task involves AI PM resumes, STAR stories, interview positioning, Agent/Workflow, Prompt Engineering, model evaluation, SFT/LoRA understanding, A/B experiments, multimodal AI, or converting non-product roles into AI PM narratives.
---

# AIPM-Pro Review

## Overview

AIPM-Pro Review turns messy real-world experience into fact-preserving AI Product Manager material.

Core principle: **package aggressively, fabricate nothing**. Reframe real work around AI PM capabilities, but do not invent model training, ownership, metrics, launches, or business results that are not supported by evidence.

## When to Use

Use this skill when the user wants to:

- Rewrite work experience for AI Product Manager roles.
- Convert internships, operations, marketing, content, data, research, design, QA, or engineering work into AI PM narratives.
- Generate STAR stories, resume bullets, interview answers, or JD-matching analysis.
- Explain Prompt Engineering, model evaluation, SFT/LoRA, RAG, Agent workflows, A/B experiments, or multimodal AI through project evidence.
- Build a reusable experience library for future resume tailoring.

Do not use this skill to fabricate credentials. If evidence is missing, mark it as a gap and create an interview-safe framing.

## Required Inputs

Ask for or infer:

1. Target role or JD:
   - AI Product Manager
   - Agent/Workflow PM
   - Model Evaluation/Data PM
   - AIGC/Multimodal PM
   - Growth/Experiment PM
   - AI Platform/Solution PM
2. Source material:
   - Old resume, project notes, PRDs, reports, spreadsheets, tickets, meeting notes, dashboards, screenshots, user research, launch reviews.
3. Evidence level:
   - Directly proven
   - Reasonably inferred
   - Missing and should be marked as a gap

## Output Modes

For a full review, produce:

1. Evidence boundary
2. Project panorama
3. End-to-end project story
4. STAR stories by module
5. AI PM capability mapping
6. Resume bullets
7. Interview talking points
8. Gap repair plan
9. Claims to avoid

For a resume-only request, produce:

1. JD keywords
2. Best project packages
3. 3-6 resume bullets
4. Interview backup stories
5. Risky claims to avoid

## Project Panorama

Always reconstruct the experience as a system, not a list of tasks.

Use this table:

| Project module | Product problem | Product actions | Evidence/source | AI PM capability |
|---|---|---|---|---|

Common modules:

- Market/user research
- Persona and scenario definition
- Agent workflow and task routing
- Memory/RAG/context system
- Prompt Engineering and output constraints
- Model evaluation and Bad Case loop
- Data analysis and metric tree
- A/B experiment and growth mechanism
- Multimodal/AIGC content production
- Commercialization or operational efficiency
- Launch, risk, and lifecycle management

## Capability Repackaging

Recombine the same evidence for different AI PM targets:

| Target role | Lead package | Evidence to emphasize | Interview expansion |
|---|---|---|---|
| Agent/Workflow PM | Intent, routing, tool use, state transitions | Flowcharts, PRDs, automation workflows | How the user task moves through the system |
| Model Evaluation PM | Eval dimensions, annotation, Bad Cases | Test cases, labels, QA logs, review tables | How quality is measured and improved |
| AIGC/Multimodal PM | Image/audio/video generation workflow | Prompt specs, asset pipelines, content review | How production quality and cost are controlled |
| Growth/Experiment PM | A/B tests and metric loops | Exposure, click, activation, retention, conversion | How product variables affect behavior |
| AI Platform PM | Tooling, dashboards, evaluation platforms | Internal tools, ops tooling, workflow specs | How teams use the platform repeatedly |
| AI Solution PM | Scenario discovery and implementation | Client/user needs, delivery plans, integration notes | How AI capability maps to business value |

## STAR Rules

For each major experience, write:

- Situation: real context and pain point.
- Task: product responsibility or problem to solve.
- Action: concrete design, evaluation, data, workflow, coordination, or launch action.
- Result: use supported numbers whenever possible.

Prefer supported output metrics over fabricated impact metrics:

- Good: "analyzed 20,000 user feedback records"
- Good: "defined 6 evaluation dimensions"
- Good: "designed 3 experiment directions"
- Risky: "improved retention by 20%" unless the source proves it

## Resume Bullet Format

Use this pattern:

```markdown
- **Capability summary:** Action + object + method + source-backed scale/result + AI PM keyword.
```

Each bullet should include:

- Capability tag: Agent, model evaluation, Prompt Engineering, SFT data loop, A/B experiment, data analysis, AIGC, RAG, commercialization.
- Product action: designed, defined, decomposed, organized, evaluated, analyzed, launched, coordinated.
- Evidence: rows, users, files, cases, modules, dimensions, experiments, workflows, versions.
- Business connection: retention, conversion, quality, efficiency, satisfaction, cost, launch risk, model iteration.

## Career Transition Packaging

When the user is not already a product manager, translate prior work into AI PM capabilities.

| Background | Transferable AI PM angle | What to emphasize | Example bullet direction |
|---|---|---|---|
| Marketing | User insight, positioning, GTM, funnel experiments | Audience segmentation, value proposition, campaign metrics, market analysis | Converted market insights into AI scenario hypotheses and product positioning |
| Operations | Process design, user lifecycle, experiment execution | SOPs, metric dashboards, retention, conversion, content/user ops | Reframed ops actions as configurable product mechanisms and A/B variables |
| Content/Community | User needs, content quality, creator ecosystem | Taxonomy, moderation, incentives, quality standards | Defined AI content quality rules and creator workflow requirements |
| Data Analyst | Metric tree, evaluation, experiment analysis | SQL/Excel/Python, dashboards, cohort analysis, causal hypotheses | Built model/product evaluation metrics and decision loops |
| UX/Design | Interaction design, prototyping, user journey | Wireframes, usability testing, information architecture | Designed AI interaction flows and failure-state handling |
| Research/Strategy | Problem discovery, industry mapping, competitive analysis | Reports, interviews, opportunity sizing, roadmap logic | Translated research into AI use cases and product requirements |
| Engineering/QA | System thinking, technical feasibility, quality control | APIs, test cases, bug triage, release process | Defined AI workflow constraints, eval cases, and rollout criteria |
| Sales/BD/Customer Success | Scenario discovery, solution mapping, stakeholder management | Client pain points, objections, adoption barriers, ROI | Converted customer problems into AI solution requirements |
| HR/Education/Training | Human assessment, learning workflows, behavior change | Rubrics, feedback loops, curriculum, coaching | Designed AI evaluation and personalized guidance scenarios |

Use this conversion logic:

1. Find the original job's repeatable decision loop.
2. Identify the user/problem/metric behind it.
3. Convert manual work into product mechanism.
4. Connect the mechanism to AI PM keywords.
5. Keep the claim fact-safe.

## Operations-to-Product Rewrite

If the source sounds operational, rewrite it as product experimentation.

Examples:

- "Sent push notifications" -> "designed recall experiment variables and metrics"
- "Configured homepage content" -> "built configurable exposure layer for entrance testing"
- "Managed user tasks" -> "designed incentive mechanism with completion and retention metrics"
- "Reviewed AI replies" -> "built model evaluation labels and Bad Case feedback loop"

Use this structure:

1. User/product hypothesis
2. Product variable
3. Control and experiment groups
4. Metrics: exposure, click, activation, completion, retention, conversion, satisfaction, cost
5. Decision loop: ship, rollback, segment, or iterate

## Prompt Engineering Packaging

Package Prompt work as a product quality system, not just "wrote prompts".

Look for:

- Thought templates or reasoning steps
- Few-shot examples
- Output format constraints
- Style and tone constraints
- Negative examples
- Bad-expression blacklists
- Regression examples
- Evaluation connection

Strong bullet pattern:

```markdown
- **Prompt Engineering:** Designed structured prompt rules for [scenario], covering reasoning steps, few-shot examples, output constraints, negative examples, and Bad Case regression criteria, turning subjective output quality into measurable dimensions.
```

## SFT / LoRA / Model Tuning Positioning

Be careful. Unless the source proves actual training ownership, do not say the user trained or fine-tuned a model.

Use product-side SFT language:

- Defined tuning objectives
- Mined Bad Cases
- Designed annotation guidelines
- Selected high-value samples
- Built eval/regression sets
- Coordinated with algorithm, QA, and annotation teams
- Defined offline and online acceptance metrics

Explain SFT to non-technical AI PM interviewers as:

1. Define the business behavior to improve.
2. Collect real user interactions, Bad Cases, and high-quality responses.
3. Convert them into instruction, `prompt/completion`, or `system/user/assistant` samples.
4. Split train/eval/regression sets.
5. Coordinate training with algorithm engineers.
6. Validate through offline eval, human review, and online A/B.

Boundary:

- CoT/few-shot/Prompt Engineering are not fine-tuning, but they prove the user can define the behavior SFT should learn.
- Convert thought templates into ideal-answer structure and evaluation dimensions.
- Convert few-shot positive/negative examples into SFT demonstration samples and regression cases.
- Convert bad-expression lists into annotation rules and negative labels.
- Convert Bad Case analysis into sample mining, training priorities, and version regression.
- Frame LoRA/QLoRA as process understanding or a proposed workflow unless actual training logs/model versions exist.

## SFT Standard Checklist

When asked to strengthen fine-tuning experience, build a product-side SFT standard:

| Standard item | Product-side definition |
|---|---|
| Tuning goal | What behavior should improve: role consistency, intent satisfaction, task completion, style, format, safety |
| Sample sources | Real user interactions, high-value sessions, support tickets, eval failures, manually corrected outputs |
| Sample admission | Complete context, clear intent, high-quality target answer, no privacy leakage, no corrupted state |
| Label taxonomy | Good/bad labels, scoring dimensions, positive examples, negative examples, boundary rules |
| Data format | `system/user/assistant`, `prompt/completion`, or domain-specific instruction format |
| Data split | Train, validation, regression, safety, and general-capability holdout sets |
| Offline eval | Quality dimensions, human review rubric, version comparison |
| Online eval | A/B metrics, user behavior, negative feedback, cost, latency, rollback conditions |
| Technical boundary | SFT/LoRA for stable behavior; RAG/memory/tools for dynamic knowledge and personalization |

## Interview Scenario Template

If asked "How would you run LoRA/SFT for this project?", answer:

1. Choose one high-value scenario or user segment as pilot.
2. Define target as stable behavior, not general intelligence.
3. Mine samples from real interactions, high-value sessions, and Bad Cases.
4. Clean privacy, duplicates, corrupted context, failed states, and low-value chatter.
5. Annotate with behavior labels and corrected ideal outputs.
6. Convert to `messages` or instruction samples.
7. Let algorithm evaluate LoRA/QLoRA vs full fine-tuning based on cost, versioning, and scope.
8. Validate with offline eval, human blind review, and online A/B.
9. Roll back if the model improves style but harms factuality, safety, latency, or user feedback.

## Fact-Preservation Rules

- Do not invent growth rates, accuracy, revenue, or launches.
- If only sample scale is known, use sample scale.
- If only project scope is known, use "defined", "designed", "analyzed", or "participated in".
- If role ownership is unclear, use "contributed to", "coordinated", or "supported".
- Mark missing proof as "evidence needed".
- Never reduce a complex project to generic "operations" if product mechanisms and metrics can be identified.

## Final Quality Check

Before returning:

- Every bullet has a capability tag.
- Every metric is source-backed or clearly marked as estimated/planned.
- The strongest AI PM keywords are represented without keyword stuffing.
- The narrative can survive an interview follow-up.
- Claims about training, launch, ownership, and business impact are conservative.
