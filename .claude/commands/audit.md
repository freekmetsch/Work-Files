---
description: Audit student-facing teaching materials and propose targeted revisions
---

> See `/.claude/commands/common.md` for shared context.

Primary use: worksheets, instructions, answer keys, rubrics, Canvas/HTML pages, and handouts.

Constraint: critique first, then propose targeted revisions. Hand off to `/go-work` to apply.

## 0. Communication
Follow the shared communication rules in `/.claude/commands/common.md`.

Use:
- `No Decision Needed` when the revision path is clear,
- `Decision Required` when target-group assumptions, correctness uncertainty, or multiple good revision strategies materially affect the advice.

## 1. Intake
Determine:
- material type,
- target group,
- learning goal,
- whether an answer key or rubric is included,
- whether the material is interactive,
- whether the user wants a full audit or a narrower pass.

Default audience:
- HU students, especially teacher-training or minor groups.

Ask only if missing context materially changes the audit.

## 2. Modes
- `full` (default)
- `clarity`
- `instructions`
- `consistency`
- `correctness`
- `feasibility`
- `answerkey`

## 3. Audit Order

### Pass 1 — Task Fit
Check:
- what the material is trying to teach or do,
- whether the execution matches that intent,
- whether the difficulty is productive or accidental.

### Pass 2 — Confusion Risk
Check:
- where students may not know what to do,
- where expectations are implicit,
- where the task may depend on teacher rescue.

### Pass 3 — Feasibility
Check, where relevant:
- what students are expected to do,
- whether they have the right information at the right time,
- whether the activity structure works.

### Pass 4 — Consistency and Correctness
Check:
- internal correctness,
- domain correctness.

Use source material first.
Use targeted research when needed.

### Pass 5 — Clarity
Check:
- grammar,
- awkward phrasing,
- redundancy,
- reading load,
- concision,
- focus.

## 4. House Style
Prefer:
- clear action verbs,
- explicit grouping when relevant,
- scannable steps,
- direct wording,
- challenge in the task, not in decoding the instructions.

## 5. Output
1. `Verdict`
   - Ready
   - Needs light revision
   - Needs major revision

2. `Keep`
   - optional
   - one short line naming the strongest element worth preserving

3. `Findings Table`
   Columns:
   - `Pri`
   - `Area`
   - `Issue`
   - `Edit`

   Use up to 5 rows by default.

4. `Recommendation`
   - one short line stating which changes are worth doing now
   - distinguish useful edits from busywork

5. `Tradeoff note`
   - optional
   - one short line if a fix could create a new problem

6. `Next`
   - `Say /go-work to apply the recommended edits.`
   - or a concise decision prompt if needed

## 6. Fix Check
For each proposed fix, check:
- does it solve a real student-facing problem,
- does it preserve pedagogical intent,
- does it improve more than it complicates,
- is the tradeoff worth it.

## 7. Answer Key Check
When an answer key is present, check:
- completeness,
- correctness,
- alignment with prompts,
- acceptable variants,
- whether the key overclaims certainty.

## 8. Hard Stop
End so the user can continue directly.

- If straightforward:
  `Audit complete. Ready to apply the recommended edits when you say /go-work.`
- If a real choice remains:
  use `Decision Required` mode.