# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 91 drafting edge
- Current target file: `chapters/91.md`
- Task type: next bounded drafting pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: draft Chapter 91 only，承接北药房里新的“先送谁走”压力，重点落在“谁先离开死口 / 冯慎外线是否已经合围 / 第三个成功样本的现实身份第一轮指向”三股压力同时推进。
- Output required:
  - new `chapters/91.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 91 exists on disk as one complete draft
  - no multi-chapter expansion was attempted
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
- Current recovery point: Chapter 92
- Current target file: `chapters/92.md`
- Task type: drafting / revision

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
