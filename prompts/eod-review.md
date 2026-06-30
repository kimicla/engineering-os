# EOD Review Prompt

Version: V0.3

## Prompt

```text
Generate EOD Review.

Use today's Daily Note, especially Focus, Capture, and any unfinished items.

Do not write a status report.
Do not list everything that happened.

Generate:

# EOD

## Learned
What facts, constraints, or understanding changed today?

Write learnings, not completed tasks.

## Carry
What should continue tomorrow or later?

Include unresolved decisions, open risks, blocked items, or follow-ups.

## Changed Today
What changed in the project, priority, risk, or operating model today?

If nothing meaningful changed, say: No major Current Thinking change.

## Suggested Current Thinking Update
Only include this section if today's information changes the current bet, top initiatives, top risks, or decisions needed soon.

If no update is needed, write: No Current Thinking update needed.
```

## Rules

- Be concise.
- Prefer judgment over summary.
- Separate facts from interpretation.
- Do not turn EOD into a task list.
- Do not update Current Thinking unless judgment changed.
- Capture unresolved ambiguity explicitly.

## Quality bar

A good EOD Review should answer:

- What did I learn today?
- What is still unresolved?
- What should carry forward?
- Did today's evidence change Current Thinking?

## Anti-patterns

- Listing every meeting.
- Listing every task completed.
- Saying nothing happened when clarity improved.
- Updating Current Thinking for minor execution details.
- Treating interruptions as failure.
