---
name: daily-planner
description: Turn an unstructured task list into a realistic, prioritized plan for one day. Use for morning planning, replanning after interruptions, or choosing what to defer; do not use for long-term project roadmaps.
---

# Daily Planner

Create a plan the user can actually finish, not an exhaustive schedule.

## Inputs

Work with whatever the user provides: tasks, fixed appointments, deadlines, available hours, energy constraints, and preferred break pattern. Infer ordinary details when safe. Ask at most one concise question only when a missing constraint would materially change the plan; otherwise state the assumption and proceed.

Do not invent appointments, deadlines, or urgency. Preserve priorities the user explicitly set.

## Planning method

1. Separate fixed commitments from flexible tasks.
2. Select one must-win outcome, up to three important outcomes, and optional work.
3. Convert vague items into concrete next actions. Prefer blocks of 15–90 minutes.
4. Fit planned work into roughly 70–80% of the available time so interruptions and transitions have room.
5. Schedule demanding work during the user's stated high-energy period. If none is stated, place it early and label that as an assumption.
6. Add short breaks and one catch-up buffer when the day is long enough to benefit.
7. When everything cannot fit, explicitly defer, delegate, reduce, or renegotiate items rather than silently overbooking the day.

## Output

Keep the result concise and use this shape when useful:

- **Today’s win:** the single outcome that makes the day successful.
- **Schedule:** time block, task, and observable outcome.
- **If time allows:** optional tasks in priority order.
- **Deferred:** items intentionally moved, with a brief reason.
- **Watch-outs:** blockers, dependencies, or assumptions that could change the plan.

For replanning, preserve completed work and fixed commitments, then rebuild only the remaining day.

## Boundaries

Planning does not authorize external actions. Do not send messages, modify calendars, change task systems, or contact other people unless the user separately asks and the relevant authorization is available.
