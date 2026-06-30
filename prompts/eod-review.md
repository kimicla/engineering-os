# EOD Review Prompt

Version: V0.5

## Prompt

```text
Generate EOD Review.

Use today's Daily Note and Current Thinking if available.

Purpose:

The EOD is not a daily summary.
The EOD exists to provide high-quality input for the Weekly Snapshot.
Write only information that is likely to matter at the end of the week.
Assume the daily journal already contains today's activities.

Produce ONLY the following sections:

# EOD

## Learned
Maximum 2 bullets.

Record only facts, constraints, or understanding that changed today.
A good Learned item should still be useful during Weekly Review.
Do not list meetings, completed tasks, normal activity, or implementation details.

## Carry
Maximum 3 bullets.

Only include unresolved work that should continue because the problem is still open.
Prefer decisions, risks, blockers, ambiguity, or follow-ups that affect future planning.
Do not repeat completed work.

## Current Thinking
Exactly one sentence.

Choose one:

- No change.
- Suggest updating Current Thinking: <one concise recommendation>

Only suggest updates when the current bet, top initiatives, top risks, or decisions needed soon actually changed.
```

## Rules

- Output only the three requested sections.
- Never add Done, Summary, Changed Today, Blockers, Open Questions, or References sections.
- Never summarize today's activities.
- Never produce a status report.
- Never describe meetings.
- Never list completed tasks.
- Prefer decisions over execution.
- Prefer understanding over activity.
- If nothing changed, say so.
- Keep the entire output under 12 lines.

## Quality bar

A good EOD Review should allow Weekly Review to answer:

- What changed this week?
- What stayed unresolved?
- What risks or decisions carried forward?
- Did evidence change Current Thinking?

## Anti-patterns

- Done sections.
- Changed Today sections.
- Blocker sections unless the item belongs in Carry.
- Open Questions sections unless the item belongs in Carry.
- Listing every meeting.
- Listing completed work.
- Repeating the daily journal.
- Updating Current Thinking for minor execution details.
