---
description: Review, finalize, commit, and push document/material changes
---

> See `/.claude/commands/common.md` for shared context.

Primary use: wrap up work on worksheets, handouts, instructions, answer keys, rubrics, Canvas/HTML pages, PDFs, and text files.

Constraint: keep wrap-up lightweight. Verify the changed material, stage only the intended files, create one sensible commit, and push automatically when the scope is clear.

## 0. Communication
Follow the shared communication rules in `/.claude/commands/common.md`.

Use:
- `No Decision Needed` when the commit scope is clear,
- `Decision Required` only when the scope is ambiguous or a meaningful problem blocks safe completion.

## 1. Final Check
Check only what is relevant:
- are the intended files the ones that changed,
- are placeholders or draft notes removed,
- are dates, labels, headings, and references correct,
- do answer keys match the final task version,
- do instructions still make sense after the edits,
- if HTML or Canvas content changed, does the final structure still read cleanly,
- if PDFs were regenerated, do they match the latest source.

## 2. Scope Check
Use one commit for one clear completed scope.

If unrelated or unfinished work is mixed in, stop and ask before committing.

## 3. Commit and Push Flow
Treat `done-docs` as authorization to:
- create one commit for the clearest completed scope,
- push automatically when the scope is clear.

Rules:
- stage only intended files,
- use a clear, scoped commit message,
- leave unrelated or unfinished files unstaged.

## 4. Commit Message Style
Use short, descriptive commit messages.

Examples:
- `audit: tighten week 7 worksheet instructions`
- `materials: revise prepositions answer key`
- `canvas: simplify peer feedback page`

## 5. Output
1. `Completed`
   - one short line saying what was finalized

2. `Checked`
   - short bullet list of the checks actually performed

3. `Commit`
   - the commit message used

4. `Push`
   - one short line confirming that the push was completed
   - or a concise blocker note if it could not be pushed

5. `Next`
   - one short line telling the user the next direct step

## 6. Hard Stop
End after commit and push.

- If successful:
  `Commit created and pushed.`
- If blocked:
  use `Decision Required` mode.
