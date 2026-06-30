# EOD Review Prompt

Version: V0.4

## Prompt

```text
Generate EOD Review.

Use today's Daily Note and Current Thinking if available.

You are updating my Engineering OS, not writing a daily status report.

Extract only information that changes future decisions.
Ignore implementation details already captured in the journal.

Produce ONLY the following sections:

# EOD

## Learned
Maximum 2 bullets.

Record only things that changed my understanding.
Do not list meetings, completed tasks, or normal activity.

## Carry
Maximum 3 bullets.

Only include work that should continue because the problem is still unsolved.
Do not repeat completed work.

## Current Thinking
Exactly one sentence.

Choose one:

- No change.
- Suggest updating Current Thinking: <one concise recommendation>

Only suggest updates when the current bet, top initiatives, top risks, or decisions needed soon actually changed.
```

## Rules

- Never summarize today's activities.
- Never produce a status report.
- Never describe meetings.
- Never list completed tasks.
- Prefer decisions over execution.
- Prefer understanding over activity.
- If nothing changed, say so.
- Keep the entire output under 15 lines.

## Quality bar

A good EOD Review should answer:

- What did I learn today?
- What still needs to continue?
- Did today's evidence change Current Thinking?

## Anti-patterns

- Done sections.
- Blocker sections unless they belong in Carry.
- Listing every meeting.
- Listing completed work.
- Repeating the daily journal.
- Updating Current Thinking for minor execution details.
