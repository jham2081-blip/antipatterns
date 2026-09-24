# Agent instructions

This repository is a focused writing-antipattern skill. Preserve its voice-specific catalog, trigger boundaries, installability, and small-scope utility rather than turning it into a generic writing platform.

Read `README.md`, `SKILL.md`, and the specific catalog/code touched by the task before editing. Treat current code and tests as implementation truth. Keep changes small, reviewable, and compatible with the documented skill behavior.

## Shared engineering handbook

This repository vendors the `software-standard` profile from `jham2081-blip/ai-agent-skills` under `engineering/ai-handbook/`, pinned by `HANDBOOK_ADOPTION.json`.

Use it with progressive disclosure: load only the skill relevant to the task. Repository-specific behavior and current files override generic handbook guidance.

When using GPT-6 Astra, Sol, or Luna for substantial work, consult `engineering/ai-handbook/field-guides/openai-gpt-6.md` for model selection, follow-through, delegation, verification, and API/harness guidance.
