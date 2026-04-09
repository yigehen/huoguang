# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 71 planning edge
- Current target file: `chapters/71.md`
- Task type: next bounded drafting pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: draft Chapter 71 only,承接周予安失联、林晚棠开口与秦姨身份揭露后的第一轮后果，重点落在“谁先去找秦姨 / 谁先追周予安 / 周明远如何压口”三股力量的碰撞。
- Output required:
  - new `chapters/71.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 71 exists on disk as one complete draft
  - no multi-chapter expansion was attempted
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
- Current recovery point: Chapter 72
- Current target file: `chapters/72.md`
- Task type: drafting / revision

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
