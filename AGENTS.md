# Daily Agent Toolkit

## Purpose

This repository is a personal workspace for small, reusable AI agents, Codex skills, plugins, prompts, and everyday workflow automations.

## Working principles

- Prefer one small, testable workflow over a large general-purpose agent.
- Keep instructions concise and store reusable workflows in clearly named folders.
- Include a short README or usage example with every tool.
- Verify behavior before describing a workflow as complete.
- Never commit passwords, API keys, access tokens, private work documents, or other sensitive data.
- Require explicit human approval before an automation sends messages, deletes data, makes purchases, changes permissions, or publishes externally.
- Preserve useful existing files and avoid unrelated changes.

## Suggested structure

- `.agents/skills/` — repository-specific Codex skills
- `agents/` — agent applications and orchestration examples
- `prompts/` — reusable prompt templates
- `tools/` — small command-line utilities
- `tests/` — checks for tools and workflows
- `docs/` — setup notes and usage guides

## Connection test

Verification marker: `DAILY_AGENT_TOOLKIT_CONNECTED`
