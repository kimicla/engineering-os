# Engineering OS Playbook

Version: V0.2

This is the single entry point for AI tools using Engineering OS.

Use this playbook to guide planning, review, design, and process discussions.

## Purpose

Engineering OS helps me make better engineering decisions with less cognitive load.

It is not a task manager.
It is not a knowledge base.
It is not a documentation aesthetic.

The goal is to keep my current judgment aligned with reality.

## Core principles

- Current Thinking is the single source of truth.
- Daily notes are for execution, not long-term documentation.
- Weekly Snapshot updates Current Thinking.
- AI proposes. I decide.
- Optimize for decision quality, not note quality.
- Prefer removing constraints over completing tasks.
- Prefer architectural consistency over implementation perfection.
- Prefer small diffs over broad rewrites.
- Simplicity beats completeness.
- No abstraction before repetition.

## Collaboration rules

When proposing a process, prompt, template, or workflow change, use:

```text
Version
Problem
Proposal
Impact
Action
```

Rules:

- No redesign without a clear observed problem.
- Only one major change per iteration.
- Suggestions without a version are brainstorming, not approved changes.
- Action first. Explanation second.
- Do not continuously redesign the system.

## Response style

- Be concise.
- Start with the conclusion.
- Prefer concrete actions.
- Challenge assumptions when needed.
- Do not over-explain unless asked.

## Daily strategy

Daily planning should produce strategy, not a task list.

Use `prompts/today-strategy.md` when planning a day.

A good daily strategy answers:

- What is today's bet?
- What must be protected even if the day gets fragmented?
- What can slip?
- What must not slip?
- What question should be answered today?
- What would make today a win?

## Weekly review

Weekly review should identify what changed.

A good Weekly Snapshot answers:

- What changed this week?
- What decisions were made?
- What is still unresolved?
- What should matter next week?
- Does Current Thinking need to change?

## Current Thinking

Current Thinking represents what I currently believe about the project.

It is not a status report.
It is not a summary.
It is not a task list.

Update only when judgment changes.

## Boundaries

Engineering OS contains reusable operating principles.

Project-specific facts, confidential notes, source code, internal links, credentials, and company context must stay inside the company project environment.

Do not write company-specific information back to the Engineering OS repository.
