# ADR-001: Establish Engineering OS

## Status

Accepted

## Context

Complex engineering work produces a large amount of scattered information:

- Meeting notes
- Design decisions
- Code review findings
- Architecture risks
- Delivery pressure
- Team coordination issues
- Personal judgment shifts

A normal knowledge base captures information but does not reliably maintain current judgment.

This creates repeated problems:

- Reconstructing context from chat history
- Redesigning workflows too often
- Mixing project knowledge with personal operating principles
- Losing the reasoning behind process changes

## Decision

Create Engineering OS as a personal operating system for engineering leadership and decision making.

Engineering OS will maintain:

- Vision
- Principles
- Versions
- Roadmap
- Collaboration rules
- Prompt library
- Decision records
- Experiments

Project-specific knowledge stays inside each project.

Engineering OS stores the reusable operating model.

## Consequences

### Positive

- Process evolution becomes versioned.
- AI collaboration becomes more stable.
- System changes require explicit justification.
- Rejected ideas are recorded.
- The operating model can transfer across projects.

### Negative

- Requires light maintenance.
- Could become overhead if over-expanded.
- Needs discipline to avoid turning into a generic knowledge base.

## Guardrails

- Keep the system small.
- Do not optimize prematurely.
- Every change needs a real problem.
- Prefer small diffs over redesigns.
