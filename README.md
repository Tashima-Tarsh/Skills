# Skills — Unified Engineering Skill Hub

A centralized, versionable **catalog and routing layer** for software engineering, AI coding, context/token efficiency, VRAM and inference, UI/UX, 3D, research, security, and production assurance.

## Getting started

1. Browse [the full 110 source registry](REGISTRY.md).
2. Read [the master agent instructions](AGENTS.md).
3. Use [the skill-router specification](skills/skill-router/SKILL.md) in your agent's compatible skills/rules directory.
4. Select a small number of task-relevant skills; inspect upstream SKILL.md and scripts before copying or executing.
5. Pin tested versions and run verification in the target project.

**Important:** Registry entries are external links, not bundled installations. Some are agent skills, others are libraries, frameworks, CLI tools or executable security software. No automatic cloning or arbitrary upstream script execution is performed.

## Routing map

| Task | Start with |
|---|---|
| Root cause, minimal fixes | Ponytail, Superpowers, Serena |
| Architecture and large repositories | Serena, Aider, Repomix |
| Save tokens and manage context | Context Engineering, Context7, LiteLLM, Langfuse |
| 70B+ VRAM and serving | llama.cpp, vLLM, SGLang, Unsloth (fine-tuning) |
| Premium UI/UX | UI UX Pro Max, UI Craft, Vercel Agent Skills |
| Research and mathematics | Scientific Agent Skills, AI Research Skills, SymPy |
| Security review | Semgrep, Trivy, Gitleaks, OWASP guidance |
| Browser and regression testing | Playwright, Vitest, Pytest, k6 |
| Full stack and infrastructure | Next.js, FastAPI, NestJS, OpenTofu, OpenTelemetry |

## Use in Kilo Code, Codex, Claude Code

Different agents discover skills in different directories and support different rule formats. Reference this repo in their project instructions, or copy the reviewed `skills/skill-router/` folder and `AGENTS.md` into their supported locations. Do not assume all agent platforms support the same installer, YAML frontmatter, hooks or MCP servers.

## Security and licensing

Only run security tests on systems you own or are authorized to test. Do not vendor third-party repos wholesale without license review. Keep credentials out of Git, review external scripts and hooks, and do not automatically grant full filesystem/network privileges to third-party skills.

## Scope

This repository is a discovery-and-orchestration hub. Future additions can include a machine-readable registry, link-health CI and tested adapters for individual agents.
