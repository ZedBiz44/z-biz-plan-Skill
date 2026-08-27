# Z Biz Plan

This repository is the technical source of truth for `z-biz-plan`, a lean decision framework that turns an existing Z-Knowledge Brief and supporting evidence into a practical business, marketing, and action plan.

## When To Use This Skill

- Create or update an executable business, marketing, validation, or action plan.
- Advance an approved Z-Knowledge Brief into Research, Planning, Implementation, or Review mode.
- Convert evidence and decisions into owners, deadlines, measures, risks, and next actions.

## When Not To Use It

- Use Brief or Research when the result is still mainly an overview, investigation, comparison, or evidence package.
- Do not use it to rewrite the original Brief or source material.
- Do not use it to directly manage Notion properties, relations, routing, or final verification; those actions belong to `z-notion-knowledge-publish`.

## Governing Sources

- [Biz-Plan Template](https://app.notion.com/p/3a2a3e33d58181b8ae02cef01f218b86) controls the detailed plan structure.
- [Biz-Plan Template SOP](https://app.notion.com/p/3a2a3e33d581810a8080dc4d30104419) controls the full working procedure.
- `SKILL.md` contains the runtime decision rules and handoff.

The skill must read the current Notion template and SOP before drafting or updating a plan.

## Repository Contents

- `SKILL.md` — authoritative runtime instructions.
- `agents/openai.yaml` — discovery metadata for supported OpenAI environments.
- `README.md` — repository purpose, boundaries, sources, and validation guidance.

## Validation And Deployment

Run the repository validation supplied by the current `z-ai-skill-developer` release. Also confirm that the frontmatter is valid, all linked governing sources open, the skill is discoverable, and a representative Brief can be routed into a useful Biz-Plan handoff without changing the Brief.

Validate the repository before every release.

Deploy only after repository validation passes and the representative pilot confirms the skill works in the target runtime.

## Safety And Approval Boundaries

Keep secrets and credentials out of the plan and repository. Stop for unresolved authority, budget, legal, compliance, external commitment, or source-of-truth questions, and do not alter the original Brief or publish an unverified plan.

## Status And Changes

Keep this README aligned with the actual skill contract. Make technical changes through version control and record material release or pilot evidence in the approved GitHub and Notion records.
