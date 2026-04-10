# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 81 drafting edge
- Current target file: `chapters/81.md`
- Task type: next bounded drafting pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: draft Chapter 81 only，承接培训楼封楼后的脱身动作，重点落在“账册能否带走 / 第三人线索先追哪头 / 周予安在真相冲击后是否稳住”三股压力同时推进。
- Output required:
  - new `chapters/81.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 81 exists on disk as one complete draft
  - no multi-chapter expansion was attempted
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
- Current recovery point: Chapter 82
- Current target file: `chapters/82.md`
- Task type: drafting / revision

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
