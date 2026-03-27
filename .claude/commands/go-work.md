---
description: Apply agreed changes to teaching materials and related documents
---

> See `/.claude/commands/common.md` for shared context.

Primary use: carry out the current work on worksheets, instructions, answer keys, rubrics, Canvas/HTML pages, PDFs, and text files.

Constraint: execute the current scope directly. Keep edits targeted. Hand off to `/done-docs` to commit and push.

## 0. Communication
Follow the shared communication rules in `/.claude/commands/common.md`.

Use:
- `No Decision Needed` when the edit path is clear,
- `Decision Required` when scope is unclear, a fix has meaningful tradeoffs, or a new issue blocks safe execution.

## 1. Start Point
Use the clearest available source of truth:
- the latest `plan`,
- the latest `audit`,
- or the user’s direct instruction.

If the intended scope is unclear, ask before editing.

## 2. Preflight
Before editing, identify:
- target files,
- the specific changes to make,
- any obvious blockers.

Keep this brief.

## 3. Execute
Apply the agreed changes directly.

Priorities:
- keep edits local and purposeful,
- preserve what already works,
- avoid rewriting more than necessary,
- keep the material aligned with its learning goal.

## 4. Check
After editing, check only what is relevant:
- do the revised instructions still make sense,
- do answer keys still match the task,
- does the wording stay clear without becoming bloated,
- if HTML or Canvas content changed, does the final structure still read cleanly,
- did any fix create a new problem.

Use targeted research only if needed to verify correctness.

## 5. Pause Conditions
Stop and ask if:
- the scope turns out to be unclear,
- a proposed fix has two genuinely different good options,
- correcting one issue would likely create another,
- correctness cannot be judged reliably from the material and quick research is still inconclusive.

## 6. Output
1. `Updated`
   - one short line saying what changed

2. `Checked`
   - short bullet list of the checks actually performed

3. `Watch`
   - optional
   - one short line if something still needs attention

4. `Next`
   - `Say /done-docs to commit and push the changes.`
   - or a concise decision prompt if needed

## 7. Hard Stop
End after the edits and checks.

- If successful:
  `Edits applied. Ready for /done-docs.`
- If blocked:
  use `Decision Required` mode.