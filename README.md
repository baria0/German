# Deutsch lernen 🇩🇪 + English upgrade 🇬🇧

A daily, **speaking-first** system to go from **A2 to B1 in about 5 months** and to **B2 by the end of 2027**, with Claude as a daily conversation partner and tutor. English is the working language of this repo, so English improves along the way.

| | |
|---|---|
| Level now | **A2** (self-assessed, November 2026) |
| Goal 1 | Confident B1 conversations by **April 2027** |
| Goal 2 | Goethe or telc **B1 exam in May 2027** |
| Goal 3 | **B2** by December 2027 (technical German, job interviews) |
| Progress | 👉 [PROGRESS.md](PROGRESS.md) |

## The files

| File | What it is |
|---|---|
| [PLAN.md](PLAN.md) | The roadmap: phases, weekly topics, checkpoints, timeline chart |
| [PROGRESS.md](PROGRESS.md) | Dashboard: streak, error rate trend, checkpoint scores, can-do checklist |
| [MISTAKES.md](MISTAKES.md) | Every mistake gets an ID, is recycled in later sessions and is retired when fixed |
| [METHOD.md](METHOD.md) | Why this method works, how German and English are learned together, false friends, Turkish advantages |
| [RESOURCES.md](RESOURCES.md) | Curated resources: the daily core stack and extras, plus Darmstadt options |
| [vocab/chunks.tsv](vocab/chunks.tsv) | Phrase deck (German, English, note, tags), importable into Anki |
| [sessions/](sessions/) | One log per session: what we did, corrections, numbers, homework |
| [CLAUDE.md](CLAUDE.md) | The tutor protocol Claude follows in every session |

## A normal day (60 to 90 minutes in total)

| Block | Time | What |
|---|---|---|
| 🗣️ Session with Claude | 30 to 40 min | Speaking practice with corrections (see below) |
| 🎧 Input | 20 to 30 min | Easy German, Nicos Weg or nachrichtenleicht (commute, gym, cooking) |
| 🃏 Anki | 10 min | Review the phrases from `vocab/chunks.tsv` |
| 🏙️ Real life | 1 moment | Use German at least once a day in Darmstadt: bakery, Mensa, shop, neighbours |

Bad day rule: **never zero**. 10 minutes of Anki or one Easy German video keeps the streak alive.

## How to start a session

1. Open a new Claude Code session on this repo.
2. Write anything, for example: `Neue Session` or `Hallo, heute habe ich 30 Minuten.`
3. Claude reads your progress, mistakes and the plan, then starts the session of the day.
4. **Use voice dictation in German** (phone keyboard microphone, language German) instead of typing. It trains speaking and pronunciation: if the dictation writes something wrong, your pronunciation needs work there.
5. At the end, Claude updates the logs and commits them.

| Day | Session type |
|---|---|
| Mon | Rollenspiel (role-play a real situation) |
| Tue | Erzählen (tell a story in the past) |
| Wed | Diskussion (discuss a video or article you consumed) |
| Thu | Uni und Arbeit (professor, group work, Hiwi interview, emails) |
| Fri | Speed-Runde (fast retrieval and translation drills) |
| Sat | Echtes Leben (report on a real German conversation) |
| Sun | Wochenrückblick (weekly review, every 4th Sunday a checkpoint) |

## Sync

Each Claude session starts from a fresh copy of the repo's **default branch**. So every session's commits must end up on the default branch, otherwise the next session forgets them.

Setup (once): the default branch should be called `main`. At the end of each session Claude pushes its working branch and merges it into `main`, if you have allowed that. If you prefer to review first, Claude opens a pull request and you merge it.
