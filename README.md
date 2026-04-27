# AgentCEO

> Most agents execute. AgentCEO manages.

Open-source Management Kernel for AI CEOs.

AgentCEO gives AI agents CEO-like management capabilities: **strategy, organization, task governance, decision control, risk escalation, and organizational learning**.

中文定位：

**AgentCEO 是一个开源 AI CEO 管理内核，让主 Agent 通过加载管理文档、Prompt Pack、Skill 与 Playbook，具备 CEO 式的管理能力。**

---

## What AgentCEO is

AgentCEO is **not**:
- a single AI persona,
- a prompt collection only,
- or a management theory book.

AgentCEO is:
- **The Management Layer for AI Agents**,
- a reusable management kernel that turns agents from **task executors** into **management agents**.

---

## Why AgentCEO?

Most AI agents can execute tasks, but often fail at management:

- They execute before clarifying goals.
- They create tasks without owners or acceptance criteria.
- They provide suggestions without decision boundaries.
- They miss risk escalation.
- They finish work without organizational learning.

**AgentCEO adds the missing management layer.**

---

## Naming System

- **Project**: AgentCEO
- **Reference Agent**: Finder
- **Core Module**: Management Kernel
- **Category**: Agent Management Layer

---

## Product Trio

1. **Management Kernel** (`/kernel`)
   - Constitution, worldview, strategy, organization, task governance, decision control, risk escalation, and organizational learning.
2. **Prompt Pack** (`/prompts`)
   - System prompts and role-specific prompts for mainstream agent platforms.
3. **Playbooks & Templates** (`/playbooks`, `/templates`)
   - Practical workflows and reusable output formats for real management scenarios.

---

## v0.1 MVP Capabilities

AgentCEO v0.1 focuses on five differentiating capabilities:

1. **Goal Clarification**
2. **Task Governance**
3. **Decision Control**
4. **Risk Escalation**
5. **Organizational Learning**

The goal of v0.1 is simple: prove that an agent loaded with AgentCEO can **manage better than a general-purpose executor**.

---

## Standard Demo

**Demo: Turn a vague founder idea into an executable project**

Input example:

```text
I want to build an AI CEO for my startup. Help me get started.
```

Expected AgentCEO behavior:
1. Identify the idea is not yet executable.
2. Clarify objective, users, resources, constraints, and success criteria.
3. Classify project type and priority.
4. Propose the minimum validation path.
5. Build task map (owner, deadline, deliverable, acceptance criteria).
6. Mark decisions requiring human confirmation.
7. Build risk register and escalation path.
8. Produce retrospective and capability-asset outputs.

---

## Repository Structure

```text
agentceo/
  README.md
  LICENSE
  ROADMAP.md
  CONTRIBUTING.md

  /kernel
  /prompts
  /playbooks
  /templates
  /examples
  /docs
```

---

## Roadmap

See [ROADMAP.md](./ROADMAP.md).

---

## Core Statement

**AgentCEO does not try to make AI “act like a CEO”. It equips agents with CEO-like management capability: judge, organize, execute, review, and evolve.**
