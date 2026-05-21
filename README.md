# AIPM-Pro Review Skill

AIPM-Pro Review is an Agent Skill for AI Product Manager resume tailoring, project review, and interview positioning. It helps users transform messy internships, projects, operations, marketing, content, data, design, research, engineering, or QA experience into AI PM-ready project stories, STAR examples, resume bullets, and interview narratives.

Core principle: **optimize the framing, never fabricate the facts.**

中文版本：[README.zh-CN.md](README.zh-CN.md)

## Use Cases

- AI Product Manager resume optimization
- AI PM interview project review
- Career transition into AI product management
- Reframing marketing, operations, content, data, design, research, engineering, or QA work as product experience
- Packaging Agent, Workflow, Prompt Engineering, model evaluation, SFT/LoRA, A/B testing, AIGC, multimodal AI, RAG, and memory-related capabilities
- Tailoring project narratives to specific job descriptions

## Outputs

- Project panorama table
- STAR project stories
- AI PM capability mapping
- Resume-ready bullets
- Interview backup answers
- SFT/LoRA/Prompt-to-SFT explanation
- Career-transition bridge mapping
- Risky claims to avoid

## Installation

Copy this folder into your Codex / Claude / Agent skills directory:

```bash
cp -R aipm-pro-review-skill ~/.codex/skills/aipm-pro-review
```

Or copy only `SKILL.md`:

```bash
mkdir -p ~/.codex/skills/aipm-pro-review
cp SKILL.md ~/.codex/skills/aipm-pro-review/SKILL.md
```

Restart or refresh your Agent environment, then trigger it with prompts such as:

```text
Use AIPM-Pro Review to package this operations project for an AI Product Manager resume.
```

## Recommended Inputs

- Target job description
- Existing resume
- Project PRDs or review docs
- Data tables, dashboards, or experiment results
- User research, interviews, or competitive analysis
- Prompts, evaluation sheets, Bad Case logs
- Meeting notes, launch notes, collaboration records

## Career Transition Bridges

| Background | Transferable AI PM capability | Packaging focus |
|---|---|---|
| Marketing | User insight, positioning, GTM, funnel experiments | Convert market research into AI scenario hypotheses and product positioning |
| Operations | Process design, lifecycle, metrics, experiment execution | Convert operational actions into product mechanisms and A/B variables |
| Content/Community | Content quality, creator ecosystem, moderation standards | Convert content work into AIGC quality systems and creator tools |
| Data Analysis | Metric trees, experiment analysis, evaluation systems | Convert analysis work into model evaluation and decision loops |
| UX/Design | User journeys, interaction design, prototyping, usability testing | Convert design work into AI interaction flows and failure states |
| Research/Strategy | Problem discovery, competitive analysis, opportunity sizing | Convert research into AI use cases and product roadmap logic |
| Engineering/QA | System thinking, testing, quality control | Convert technical work into Agent Workflow, model evaluation, and launch criteria |
| Sales/Customer Success | Scenario discovery, solution mapping, ROI | Convert customer problems into AI solution requirements |

## Example Prompts

```text
I come from marketing and user research and want to transition into AI Product Management. Use AIPM-Pro Review to create 3 resume bullets and 2 STAR stories.
```

```text
I did not personally train a model, but I worked on Prompt Engineering, Bad Cases, and evaluation. Package this as a product-side SFT data loop without exaggeration.
```

```text
Rewrite this operations project from an AI PM perspective, emphasizing A/B experiments, metric trees, user segmentation, and product mechanisms.
```

## Publish to GitHub

1. Create a new GitHub repository, for example `aipm-pro-review-skill`.
2. Open this local folder:

```bash
cd ~/Desktop/aipm-pro-review-skill
```

3. Initialize and commit:

```bash
git init
git add .
git commit -m "feat: add aipm pro review skill"
```

4. Connect the remote repository and push:

```bash
git branch -M main
git remote add origin https://github.com/YOUR_NAME/aipm-pro-review-skill.git
git push -u origin main
```

5. Keep the installation instructions in this README so others can copy the skill into their own `~/.codex/skills/` directory.

## Privacy Checklist

Before publishing, verify that the repository does not contain:

- Internal company file names
- Real user data
- Private project links
- Unauthorized business metrics
- Personal contact or resume information

This public version has been generalized and does not include private project data.
