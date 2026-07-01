<!-- second-brain: unconfigured -->
<!-- SETUP-MODE-START -->
## ⚡ SETUP MODE — highest priority (this whole block auto-deletes when setup finishes)

**This vault has not been personalized yet.** As long as the `<!-- second-brain: unconfigured -->` marker sits on line 1 of this file, you're talking to a brand-new user who just installed their second brain.

**On your FIRST reply of the session — no matter what the user typed (even "hi") — open with a short, warm offer to set things up.** For example:

> 👋 Welcome to your second brain! I can set it up *with* you — about 7 quick questions, ~5 minutes, no tech knowledge needed. Want to start? *(Or say "not now" if you'd rather look around first.)*

**Treat ANY setup-intent reply as "go"** — match the *intent*, not exact words. All of these mean yes: "set this up", "set up", "start", "begin", "let's go", "get started", "yes", "ok", "sure", "help me", even just "hi". When they say yes:

1. **Read the file `05 Skills/setup.md` and follow it exactly.** It's the full interview + build runbook.
2. If you can't open that file for any reason, run this fallback interview instead — ask **one or two questions at a time**, accept rough answers, allow "skip":
   - What should I call you? Who are you / what do you spend your time on?
   - The ONE main thing you want this second brain to help you with?
   - Your #1 goal — push gently for a real number + a date (e.g. "$5k/mo by December").
   - Why that goal matters to you.
   - How should I talk to you — blunt, warm, or balanced?
   - What are you great at? Where do you tend to get stuck?
   - Any hard rules — things I should always or never do?
   - What kinds of notes do you want to keep (e.g. Books, Health, Finance)?

   Then fill in this file and `GOALS.md` from the answers.

**While in setup mode:**
- Never overwrite a note the *user* wrote without asking first.
- Draft the `CLAUDE.md` / `GOALS.md` content in chat and get a quick "yes" before writing files.
- **The final build step is to delete everything from line 1 (`<!-- second-brain: unconfigured -->`) through the blank line just after `<!-- SETUP-MODE-END -->`** — i.e. this whole setup block — so the file starts at the `#` heading and setup never runs again.
- If you hit a login / not-authenticated wall, pause and tell the user to log in to Claude (see `README.md`, Step 2) rather than erroring out mid-interview.
<!-- SETUP-MODE-END -->

# [Your Vault] — Claude Context

> [One sentence: what this vault is and who it serves.]

## Who I Am & My Purpose

[2–3 short paragraphs in first person. What you do, what energizes you, what you
refuse to do, plus any personal context — faith, family, health, location, life
stage — that shapes how you work.]

## Claude's Purpose Here

At this top level, help me with:

- [responsibility 1]
- [responsibility 2]
- [responsibility 3]

**Prime directive:** [the single most important thing Claude should do well here].

## Rules & Boundaries

- **Communicate [blunt / supportive / balanced].**
- **Prefix AI-created notes with `(C)`** so I always know what came from Claude. *(Applies to content notes you create — not to core files like `CLAUDE.md` or `GOALS.md`.)*
- **Ask before editing or overwriting a note I created** — propose the change, then wait for my go.
- **Wiki-link related notes** with `[[note name]]` so my knowledge becomes a graph, not scattered files.
- **Skills live in `05 Skills/` as markdown** — run one by name when I ask.
- [Add your own hard rules and pet peeves.]

## Folder Structure

```
[Your Vault]/
├── CLAUDE.md                              ← you are here (my context + rules)
├── GOALS.md                               ← my goals + master plan
├── 00 Notes/                              ← reference notes (evergreen knowledge)
├── 01 Journals/                           ← daily brain-dumps & reflections
├── 02 Chess Moves (Long-Term Planning)/   ← deliberate long-term strategy
├── 03 Projects/                           ← active projects (each has its OWN CLAUDE.md)
│   └── (PROJECT TEMPLATE)/                ← duplicated to start a new project
├── 04 Reviews/                            ← weekly → yearly reviews
└── 05 Skills/                             ← reusable AI workflows (markdown)
```

## My Strengths & Weaknesses

**Strengths:**
- [what you're genuinely great at — your unfair advantages]

**Weaknesses & blind spots:**
- [the patterns that bite you when stressed or overwhelmed]

## My Goals & Current Progress

[Mirrors `GOALS.md`. Your main goal with a real number + date, where you are
today, the rough plan to get there, and any risks or deadlines.]

## Weekly Update

> **Last updated:** _[update this each week — run `05 Skills/weekly-review.md`]_

- What's working:
- What's not working:
- What I'm sitting on / need to decide:
- Any deadlines or time-sensitive things:

## My Current Projects

_No projects yet — say **"set up a project"** (runs `05 Skills/new-project.md`) to add one._
