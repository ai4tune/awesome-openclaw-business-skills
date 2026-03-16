# awesome-openclaw-business-skills

Practical OpenClaw skills for business workflows, AI adoption, and enterprise productivity.

一个聚焦企业效率与 AI 落地场景的实用 skills 仓库，公开基础版 skills，并持续沉淀真实业务样板。

[Quick Start](#quick-start) · [Skill Catalog](#skill-catalog) · [Use Cases](#enterprise-use-cases) · [For Enterprise](#free-vs-custom) · [Contributing](#contributing)

## At A Glance

**What it is**

A public sample repository of practical OpenClaw business skills.

**Who it is for**

Operators, consultants, sales teams, internal AI champions, and anyone trying to make enterprise AI useful in everyday work.

**What problem it solves**

It helps teams start from small, repeatable business workflows instead of vague AI experiments.

## Why This Repo Exists

Many teams know AI matters but still do not know which small business workflow to start with.

Many public skills look impressive in demos but fail in real work because they ignore role context, output structure, and operational constraints.

This repository focuses on baseline business skills that are practical, reusable, and easy to understand in 30 seconds.

## Quick Start

1. Browse the [skill catalog](#skill-catalog) and pick a workflow close to your day-to-day work.
2. Open the skill folder under `skills/` and read its README.
3. Check the example input and output to understand the quality bar.
4. Reuse the public baseline version directly, or adapt it for your own team workflow.

If you are new to the repo, start with [docs/getting-started.md](docs/getting-started.md) and [docs/enterprise-use-cases.md](docs/enterprise-use-cases.md).

## Skill Catalog

These are the first three representative skills in the repository. They are intentionally simple, practical, and easy to understand.

| Skill | 场景 | 输入 | 输出 | Level |
| --- | --- | --- | --- | --- |
| [Meeting Minutes](skills/meeting-minutes/README.md) | 会议纪要 | 会议记录、转写文本、聊天摘录 | 结论、待办、责任人、风险 | Free |
| [Client Follow-up](skills/client-followup/README.md) | 客户跟进 | 拜访记录、聊天记录、销售备注 | 需求、顾虑、下一步动作、建议话术 | Free |
| [Weekly Report](skills/weekly-report/README.md) | 周报整理 | 零散工作记录、任务清单、会议摘录 | 结构化周报、重点成果、风险与下周计划 | Free |

### Why These Three First

- `meeting-minutes` shows clear operational value inside almost every team
- `client-followup` connects directly to sales and consulting workflows
- `weekly-report` demonstrates how AI can reduce recurring reporting friction

Upcoming skill ideas are tracked in [ROADMAP.md](ROADMAP.md).

## Representative Skills

### Meeting Minutes

Best for turning transcripts or raw meeting notes into decisions, action items, owners, and risks.

### Client Follow-up

Best for transforming visit notes or chat history into client goals, concerns, and follow-up actions.

### Weekly Report

Best for converting scattered weekly notes into a concise update a manager can skim quickly.

## Enterprise Use Cases

- Sales follow-up after client meetings and demos
- Internal meeting recap for fast execution
- Management reporting from fragmented work logs

More detailed examples live in [docs/enterprise-use-cases.md](docs/enterprise-use-cases.md).

## Repo Structure

```text
awesome-openclaw-business-skills/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── ROADMAP.md
├── CHANGELOG.md
├── .github/
├── docs/
├── skills/
├── templates/
└── assets/
```

## Free vs Custom

This repository focuses on reusable baseline skills.

For industry-specific, workflow-heavy, or enterprise-integrated versions, custom adaptations are possible.

Public:

- General business scenarios
- Single-skill or short workflow tasks
- No dependency on private enterprise knowledge
- Fast-to-understand baseline examples

Custom:

- Industry-specific versions
- Multi-step workflows with role routing
- Enterprise knowledge base or internal policy integration
- Deeply embedded versions tied to customer process design

## For Enterprise

This repo is designed to work as:

- A practical sample library for enterprise AI adoption
- A public portfolio of real business workflow design
- A repeatable entry point for consulting, workshops, and courses

If you want a tailored version for your function, industry, or internal process, use the issue templates to describe your use case first.

## Contributing

Contributions are welcome, especially:

- New business use cases
- Better examples and edge cases
- Improvements to output structure and guardrails
- Documentation fixes

Start with [CONTRIBUTING.md](CONTRIBUTING.md). For new ideas, open a request via the issue templates in `.github/ISSUE_TEMPLATE/`.

## Roadmap

Current direction is tracked in [ROADMAP.md](ROADMAP.md).

Short term priorities:

- Strengthen the first three representative skills
- Publish more input and output examples
- Add enterprise workflow templates
- Add advanced custom skill showcases

## Docs

- [Getting Started](docs/getting-started.md)
- [Skill Design Principles](docs/skill-design-principles.md)
- [Enterprise Use Cases](docs/enterprise-use-cases.md)
- [FAQ](docs/faq.md)

## License

Released under the [MIT License](LICENSE).

## Collaboration

- For new skill ideas, open a `Skill Request`
- For enterprise scenarios, open a `Use Case Request`
- For cooperation or customization, start with a GitHub issue so the workflow and constraints are clear
