# NEXT_STEP.md

## Resume pointer
- Current recovery point: Chapter 111 drafting edge
- Current target file: `chapters/111.md`
- Task type: next bounded drafting pass
- Pointer rule: this is a temporary next-action pointer, not a permanent chapter anchor

## Next bounded task
- Goal: draft Chapter 111 only，承接第110章电话里“川先生”的活声音，先写北药房这一边如何稳住夏秘书、判断电话真假，并只掀一层：确认旧秘书档案柜是不是今晚就会被转移，谁最可能先去碰那把钥匙。不要立刻切成三线齐爆。
- Output required:
  - new `chapters/111.md`
  - one short entry appended to `PROGRESS.md`
  - this file rewritten with the next recovery point after the run
- Done when:
  - Chapter 111 exists on disk as one complete draft
  - 只推进北药房/秘书口这一层，不同章同时掀育衡和老宅三线大爆
  - `PROGRESS.md` and `NEXT_STEP.md` were updated before the run ends

## Update rule after completion
After finishing this task, overwrite this file with the new pointer, for example:
|- Current recovery point: Chapter 112
|- Current target file: `chapters/112.md`
|- Task type: drafting / revision

Do not leave an outdated chapter pointer here after progress has moved on.

## Run guardrails
1. Only work on the target in this file during this run.
2. Do not continue into the next chapter unless this file is explicitly updated for a future run.
3. If more work is needed, record it as the next task instead of continuing indefinitely.
4. If the session stalls, restart from this file in a fresh session.
