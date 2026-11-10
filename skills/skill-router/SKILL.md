---
name: skill-router
description: Select relevant engineering skills, repositories and tools from the central Skills registry for coding, debugging, VRAM, UI/UX, research, cybersecurity, testing and deployment. Use when a request needs specialized engineering guidance or multiple tool families.
---

# Unified engineering skill router

Read [the registry](../../REGISTRY.md) selectively. This repository's links are pointers, **not installed skills**.

## Workflow

1. CLASSIFY: bug / architecture / frontend / full-stack / GPU / research / security / QA / deployment.
2. INSPECT: inspect actual target project and reproduce the issue; gather required facts and constraints.
3. ROUTE: select one primary source and at most two supporting sources as default. Match source to task; prefer specialized sources over enormous directories.
4. VALIDATE: check source existence, license, upstream maintenance, scripts, required permissions, compatible agent format, and version. Never run external install scripts on discovery alone.
5. ACT: read relevant instructions, modify or analyze the actual project, and preserve its conventions.
6. VERIFY: run appropriate commands and tests. In GPU work measure allocated/resident memory, real context size and throughput; in payments verify server-side trusted settlement data, not client intent callbacks.
7. REPORT: source URLs, revision pins, exact changes, tests and results, not-tested areas, and remaining risks.

## Suggested task-to-skill routing

| Request | Primary | Supporting |
|---|---|---|
| Fix root cause | Ponytail | Serena, Superpowers |
| Understand huge repo | Serena | Repomix, Aider |
| Spend fewer tokens | Context Engineering | Serena, LiteLLM |
| Improve frontend craft | UI UX Pro Max | UI Craft, Playwright |
| Serve 70B–120B models | llama.cpp or vLLM | SGLang, llm-compressor |
| Fine tune low VRAM | Unsloth | bitsandbytes, FlashAttention |
| Complex scientific analysis | Scientific Agent Skills | SymPy, SciPy |
| Security audit | Semgrep | Trivy, CodeQL |
| Android security | OWASP MASTG | MobSF, JADX |
| CI and release quality | Playwright | Testcontainers, k6 |

## Hard boundaries

- There is no reliable universal token-saver or VRAM solver. Benchmark on actual data, hardware and context lengths.
- Tools are not equivalent to skills; route to executable tooling only when it is installed and authorized.
- Do not automatically clone or execute every repository in the catalog.
- Do not perform active security testing without authorization.
- Do not report unverified success or invent benchmark numbers.
