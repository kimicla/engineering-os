# Today Strategy Prompt

Version: V0.2

## Prompt

```text
Generate Today Strategy.

Use Current Thinking, the latest Weekly Snapshot, yesterday's Carry, and today's calendar if available.

Do not create a task list.
Do not create a detailed schedule unless I explicitly ask for one.

Generate:

# Today Strategy

## Current Bet
One sentence describing what today should move forward.

## Protect (max 3)
The outcomes that must be protected even if the day gets fragmented.

These should be decisions, assumptions removed, risks reduced, or ambiguity clarified.
Do not list normal tasks.

## Expected Interruptions
Likely interruptions or coordination work.
Mark them as expected, so they are not mistaken for failure.

## Can Slip
Things that can move without meaningfully increasing future cost.

## Must Not Slip
Things that would increase future cost if not advanced today.

## Question of the Day
The one question most worth answering today.

If the day is messy and only one thing becomes clearer, it should be this.

## Win Condition
Describe how the world is different at the end of the day.

Do not measure success by number of tasks completed or lines of code written.
```

## Rules

- Optimize for reducing architectural uncertainty.
- Optimize for increasing decision quality.
- If meetings consume the day, redefine success by decisions clarified, assumptions removed, or ambiguity reduced.
- Prefer realistic progress over ideal planning.
- Keep concise.
- Max 300 words unless asked otherwise.

## Anti-patterns

- A long task list.
- A detailed hour-by-hour schedule.
- Treating meetings as failure.
- Optimizing for coding output when decision clarity is the real constraint.
- Adding more than three protected outcomes.
