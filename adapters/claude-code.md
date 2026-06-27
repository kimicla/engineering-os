# Claude Code Adapter

Use this file as a local adapter for Claude Code.

## Recommended setup

In a company project, create a local-only file:

```text
CLAUDE.local.md
```

Add it to `.gitignore`:

```text
CLAUDE.local.md
```

Then reference Engineering OS from that local file.

## Example `CLAUDE.local.md`

```markdown
# Personal Operating Instructions

Use my Engineering OS rules from:

@/Users/yourname/projects/engineering-os/collaboration.md
@/Users/yourname/projects/engineering-os/principles.md
@/Users/yourname/projects/engineering-os/prompts/staff-chief-of-staff.md

## Company Project Boundary

Do not write any company-specific information back to the Engineering OS repo.

Engineering OS is only an operating model.
This company repository is the source of project-specific facts.

## Response Style

- Be concise.
- Action first.
- Prefer decisions over task lists.
- Prefer architectural consistency over implementation perfection.
- Challenge assumptions when needed.
- Do not redesign the workflow without a clear observed problem.

## Process Change Rule

For any proposed process change, use:

- Version
- Problem
- Proposal
- Impact
- Action
```

## Usage rule

Engineering OS should guide how Claude Code thinks and responds.

It should not receive company-specific source code, project details, internal links, or confidential notes.
