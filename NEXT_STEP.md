# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 86 drafting edge
- Current target file: `chapters/86.md`
- Task type: next bounded drafting pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: draft Chapter 86 only，承接北药房门外第三方敲门后的第一轮应对，重点落在“先开哪扇门 / 冯慎如何逼压 / 沈临舟旧号到底是谁在用”三股压力的即时碰撞。
- Output required:
  - new `chapters/86.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 86 exists on disk as one complete draft
  - no multi-chapter expansion was attempted
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
- Current recovery point: Chapter 87
- Current target file: `chapters/87.md`
- Task type: drafting / revision

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
