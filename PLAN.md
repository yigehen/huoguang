     1|# PLAN.md
     2|
     3|<!-- OpenClaw resumable workflow scaffold -->
     4|
     5|## Project
     6|- Name: 《火光深处等春来》
     7|- Workspace: `/root/book-writing/projects/huoguang`
     8|
     9|## Long-term objective
    10|- Keep the novel project editable in bounded runs without relying on a single long-lived ACP child session.
    11|- Ensure every meaningful run leaves enough file state behind to resume cleanly after interruption.
    12|
    13|## Working method
    14|1. One run handles one bounded unit only.
    15|2. Prefer one chapter / one scene / one revision pass per run.
    16|3. Every run must update `PROGRESS.md` and `NEXT_STEP.md` before ending.
    17|4. Use files for continuity, not persistent session memory.
    18|5. If a run stalls, restart from `NEXT_STEP.md` in a fresh session.
    19|
    20|## Project assets
    21|- `README.md` — project overview
    22|- `outline/` — structure / high-level plan
    23|- `characters/` — character reference
    24|- `chapters/` — manuscript chapters
    25|- `notes/` — supporting notes
    26|
    27|## Allowed task shapes
    28|- Draft one chapter
    29|- Revise one chapter
    30|- Fix one scene
    31|- Sync outline / character notes
    32|- Produce one progress summary
    33|
    34|## Anti-stall rule
    35|- Never queue a whole-book rewrite into one ACP run.
    36|- Split long work into explicit, finishable units.
    37|