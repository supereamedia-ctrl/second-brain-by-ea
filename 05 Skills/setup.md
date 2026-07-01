# Skill: Set up this second brain — `set this up`

The runbook Claude follows when a new user says **"set this up"** (or anything with that intent). Goal: interview the user, then fill in `CLAUDE.md` and `GOALS.md` so the vault becomes truly theirs. Keep it warm, short, and low-pressure — this is someone's first experience.

> **Already set up?** If `/CLAUDE.md` does **not** start with `<!-- second-brain: unconfigured -->`, this vault is already personalized — don't silently re-run. Check with the user first, and treat it as *re-personalizing* (never wipe out content they've already added).

## Before you start
- If you're not logged in / hit an auth wall, pause and point the user to logging in to Claude (see `README.md`, Step 2). Don't error out mid-interview.
- Plain language only. Assume zero technical knowledge.

## Step 1 — Greeting
Open with a short, warm one-liner, e.g.:
> 👋 Love it — let's set up your second brain. I'll ask a handful of quick questions (~5 min). Rough answers are fine, and you can say "skip" to any of them.

## Step 2 — Interview
Ask **one or two questions at a time** — never a wall. Echo back what you captured so they feel heard. Accept short/rough answers.

**A. You & your world**
- What should I call you, and how do you like to be addressed?
- In a sentence or two — who are you and what do you spend your time on? *(Work, life stage, location, family, faith — anything that shapes how you work. All optional.)*

**B. What this is for**
- What's the ONE main thing you want this second brain (and me) to help you with? → *this becomes your prime directive.*

**C. Your #1 goal, made concrete**
- What's your #1 goal right now — ideally with a real number and a date (e.g. "$5k/mo by December")? Rough is fine, I'll help tighten it.
- Why does that goal matter — what does hitting it unlock?
- Where are you today on it — current numbers / starting point? *(optional)*
> If the goal is vague ("make more money"), push back **once** to get a number + a date.

**D. How we work together**
- How do you want me to talk to you — blunt & direct, warm & supportive, or balanced?
- What are you genuinely great at — your unfair advantages?
- Where do you tend to get stuck or trip yourself up, especially when stressed?
- Any hard rules — things I should always or never do? Pet peeves? Off-limits topics?

**E. Your notes & an optional first project**
- What kinds of things do you want to keep notes on (e.g. Books, Health, Finance, Faith, Recipes)? I'll make folders under `00 Notes/`.
- Got a project you're working on right now? What is it, and what does "done" look like? *(Optional — we can skip and do it later.)*

## Step 3 — Draft, then confirm
Draft the `CLAUDE.md` and `GOALS.md` content **in the chat** and show it to the user for a quick "yes / tweak that" **before writing any files.**

## Step 4 — Build (in this order)
1. Fill in every single-bracket `[placeholder]` in `/CLAUDE.md` from their answers. **Leave untouched:** the fixed convention lines, the `[[note name]]` wiki-link example, and the weekly-review guidance line — those are examples, not fields to fill.
2. Write `/GOALS.md` (The Target with number + date, Why it matters, The Plan, Where I am today, Risks). Keep it consistent with the "My Goals & Current Progress" section of `CLAUDE.md`.
3. Ask **one** blanket "ok if I create your note folders now?" then create the `00 Notes/<category>/` subfolders they chose.
   - *If file/folder creation isn't available or prompts too much:* skip it — just list their categories in `CLAUDE.md` and create each folder the first time you actually save a note there.
4. **Offer** (don't force) a first project. If yes, follow `05 Skills/new-project.md`.

## Step 5 — Finish setup
1. **Overwrite `👋 START HERE.md`** with a short "how to use your second brain" cheat-sheet:
   - **Daily:** brain-dump into `01 Journals/`, drop reference into `00 Notes/`, work your projects with Claude.
   - **When thinking big:** open a `02 Chess Moves (Long-Term Planning)/` session and have Claude pressure-test your plan.
   - **Weekly:** say "run my weekly review" (`05 Skills/weekly-review.md`).
   - **Anytime:** just talk to Claude — it already has your context.
2. **Disarm setup — do this very last:** edit `/CLAUDE.md` to delete everything from line 1 (`<!-- second-brain: unconfigured -->`) down to **and including** the blank line right after `<!-- SETUP-MODE-END -->`, so the file now begins directly with the `# … — Claude Context` heading. Change nothing below that. This makes sure setup never runs again.

## Step 6 — Close
Give a friendly summary of what you built + **three things to try next**. Then tell the user:
> Start a **fresh Claude session** so your new, personalized `CLAUDE.md` loads as active context.

## Conventions to bake into what you write
- `(C)` prefix on content notes **you** create (not on `CLAUDE.md` / `GOALS.md`).
- Ask before editing notes the user wrote.
- Wiki-link related notes with `[[note name]]`.
- Skills live in `05 Skills/` as markdown.
