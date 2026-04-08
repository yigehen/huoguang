     1|# RUNBOOK.md
     2|
     3|## Purpose
     4|This file explains how to continue 《火光深处等春来》 safely when ACP sessions time out, stall, or get rebuilt.
     5|
     6|## Core rule
     7|Project continuity lives in files, not in one long-lived ACP child session.
     8|
     9|Read these first before any writing/revision run:
    10|1. `PLAN.md`
    11|2. `PROGRESS.md`
    12|3. `NEXT_STEP.md`
    13|4. `CHANGELOG.md` (if workflow/process changed)
    14|
    15|## Standard operating mode
    16|- One run = one bounded task.
    17|- Preferred scope: one chapter / one scene / one revision pass.
    18|- End every run by updating `PROGRESS.md` and replacing `NEXT_STEP.md`.
    19|- Never use a whole-book rewrite as one continuous ACP run.
    20|
    21|## If the session stalls or times out
    22|1. Stop trying to revive the old ACP child session.
    23|2. Start a fresh session.
    24|3. Read `PLAN.md`, `PROGRESS.md`, and `NEXT_STEP.md`.
    25|4. Execute only the task in `NEXT_STEP.md`.
    26|5. At the end, update `PROGRESS.md` and overwrite `NEXT_STEP.md`.
    27|
    28|## Current recovery target
    29|- Read `NEXT_STEP.md` as the live pointer.
    30|- The chapter/file named there is temporary and must be updated after each completed run.
    31|- Current bounded next task at the time of this update: revise `chapters/55.md` only.
    32|- Do not continue into chapter 56 in the same run unless `NEXT_STEP.md` is rewritten for that next run.
    33|
    34|## Good command pattern
    35|Tell the agent something like:
    36|- Read `/root/book-writing/projects/huoguang/PLAN.md`, `PROGRESS.md`, and `NEXT_STEP.md`, then do only the single bounded task in `NEXT_STEP.md`. Before ending, update `PROGRESS.md` and `NEXT_STEP.md`.
    37|
    38|## Bad pattern to avoid
    39|- Continue the old stuck session.
    40|- Keep writing across multiple chapters in one run.
    41|- Depend on session memory instead of files.
    42|