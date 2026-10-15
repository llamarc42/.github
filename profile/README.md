# llamarc42

llamarc42 is a documentation-first, local-first framework for preserving
authoritative engineering knowledge and architectural decisions, independently
of any particular AI model, agent, or development tool.

## Why it exists

Project purpose, constraints, architecture, and decisions are often scattered
across conversations, prompts, and individual experience. llamarc42 gives that
knowledge a durable, project-owned, human-readable home whose authority is
explicit and reviewable.

Engineers and architects maintain the documentation. People and AI-assisted
workflows may consume the same material, but tools do not become the source of
truth and cannot silently replace accepted project knowledge.

## Repository roles

- [`docs`](https://github.com/llamarc42/docs) owns authoritative contracts,
  ADRs, current guidance, and preserved history.
- [`core`](https://github.com/llamarc42/core) is the planned reusable C#
  implementation of accepted discovery, validation, template, and
  initialization behavior.
- [`cli`](https://github.com/llamarc42/cli) is the planned command surface over
  Core.
- [`powershell`](https://github.com/llamarc42/powershell) preserves the earlier
  local-copilot prototype as historical and reference material.
- [`api`](https://github.com/llamarc42/api) is deferred for v0.1.
- [`llamarc42.con`](https://github.com/llamarc42/llamarc42.con) is an
  independent project; any future integration is optional and separately
  governed.

Core and CLI v0.1 are planned work; they are not yet complete. Multi-repository
federation and Documentation Contract v0.2 are not current capabilities.

## Start here

Read the [current project definition](https://github.com/llamarc42/docs/blob/main/projects/llamarc42/project.md),
the [accepted contracts](https://github.com/llamarc42/docs/tree/main/projects/llamarc42/specifications),
and the [three-phase roadmap](https://github.com/llamarc42/docs/blob/main/projects/llamarc42/quality/roadmap.md).
