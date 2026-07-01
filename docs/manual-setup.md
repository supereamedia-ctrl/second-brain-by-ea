# 🧠 Manual Setup & Deep Guide

> **You probably don't need this page.** Just open the vault in Obsidian and type **`set this up`** — Claude builds everything for you (see the [README](../README.md)).
>
> This is the **manual / advanced** path, the full explanation of *why* the system is shaped this way, and the optional bonus setups (phone, sync).

---

## 🌟 What this actually is

Two simple tools working together:

- **Obsidian** — a free notes app. Every note is just a plain `.md` (Markdown) text file in a folder on your computer. No lock-in, yours forever.
- **Claude** — an AI that works *inside* that folder (via the **Claudian** plugin, which runs **Claude Code** under the hood). It reads a special file called `CLAUDE.md` at the start of every session, so it always knows who you are, what your goals are, and how you want it to behave.

Put them together and you get a **personal operating system**: a place to store everything, and a smart partner that already has all your context.

### The mental model: two layers

1. **The top layer (this vault)** — your "life OS." Big-picture goals, journals, notes, reviews, long-term strategy. Its `CLAUDE.md` is the manager who knows the whole picture.
2. **Projects (`03 Projects/`)** — each project is its own mini-vault with its *own* `CLAUDE.md`. When you work inside a project, Claude zooms into that context — a specialist who goes deep on one thing.

---

## 📁 The folder structure explained

```
Second Brain/
├── CLAUDE.md          ← Your AI's context + rules (read every session)
├── GOALS.md           ← Goals, targets, master plan
├── 00 Notes/          ← Reference notes (evergreen knowledge)
│   ├── Books/
│   ├── Courses/
│   └── Videos/        ← rename/add your own: Health, Finance, Faith, Recipes…
├── 01 Journals/       ← Daily / running journals
├── 02 Chess Moves (Long-Term Planning)/   ← Strategic thinking sessions
├── 03 Projects/       ← Active projects — each gets its OWN CLAUDE.md
│   └── (PROJECT TEMPLATE)/   ← Duplicate this to start a new project
├── 04 Reviews/        ← Your review cadence
│   ├── Weekly Reviews/
│   ├── Monthly Reviews/
│   ├── Quarterly Reviews/
│   └── Yearly Reviews/
└── 05 Skills/         ← Reusable AI workflows saved as markdown
```

| Folder | What goes here |
|---|---|
| **CLAUDE.md** | Who you are, what you want Claude to do, your rules, goals. The AI reads this first. |
| **GOALS.md** | Your concrete goals and the plan to reach them. |
| **00 Notes** | Reference material — book notes, course notes, ideas, anything evergreen. |
| **01 Journals** | Free-form journaling. Daily logs, brain-dumps, reflections. |
| **02 Chess Moves** | Deliberate long-term strategy. Think 3–5 moves ahead, then have Claude pressure-test them. |
| **03 Projects** | One folder per active project, each with its own `CLAUDE.md` and its own idea→process→output flow. |
| **04 Reviews** | Weekly / monthly / quarterly / yearly reviews to keep the whole system current. |
| **05 Skills** | Repeatable AI workflows written as markdown (e.g. `setup`, `new-project`, `weekly-review`). Run them by name. |

---

## 🧩 What are "Skills"?

A **skill** is just a markdown file describing a repeatable workflow. Instead of re-explaining a task every time, you write it down once in `05 Skills/` and then tell Claude *"run my weekly-review skill."* This vault ships with three:

- **`setup`** — the interview that personalizes your `CLAUDE.md` and `GOALS.md` (this is what `set this up` runs).
- **`new-project`** — scaffolds a new project by copying `(PROJECT TEMPLATE)`.
- **`weekly-review`** — runs your weekly review and keeps every `CLAUDE.md` current.

Write your own for anything you do repeatedly.

---

## 📜 Conventions (the small rules that keep it clean)

- **`(C)` prefix** — any *content note* the AI creates gets a `(C)` prefix, so you always know what came from you vs. from Claude. (Core files like `CLAUDE.md` / `GOALS.md` are exempt.)
- **Ask before editing** — Claude proposes changes to *your* notes and waits for your go, rather than overwriting them.
- **Wiki-link everything** — connect related notes with `[[note name]]` so your knowledge becomes a graph, not scattered files.
- **Skills live as markdown** — reusable workflows go in `05 Skills/` as `.md` files.

You can change any of these — just write your preference into `CLAUDE.md` so Claude follows it.

---

## 🗓️ How to actually use it (daily / weekly)

- **Daily:** brain-dump into `01 Journals/`, drop reference notes into `00 Notes/`, and work your projects with Claude.
- **When thinking big:** open a `02 Chess Moves` session — plan your next moves, then let Claude poke holes in them.
- **Weekly:** say *"run my weekly review."* Update goals, mark progress, adjust course.
- **Anytime:** just talk to Claude. It already has your context — ask it to plan, draft, decide, or think alongside you.

---

## 🛠️ Building it by hand (if you skipped `set this up`)

The automated `set this up` flow does all of this for you. If you'd rather do it manually:

### 1. Install Claude Code + log in
Claudian runs **Claude Code** under the hood, so install it first and log in (needs a paid Claude plan):

- **Mac / Linux:** `curl -fsSL https://claude.ai/install.sh | bash`
- **Windows (PowerShell):** `irm https://claude.ai/install.ps1 | iex`

Then run `claude` and follow the browser login. Full guide: <https://code.claude.com/docs/en/quickstart>

### 2. Install Obsidian + the Claudian plugin
1. Download and install [Obsidian](https://obsidian.md) and **Open folder as vault** on this folder.
2. **Settings → Community plugins →** turn them on **→ Browse →** search **Claudian → Install → Enable**.
   *(Claudian is open-source: <https://github.com/YishenTu/claudian>)*

### 3. Fill in `CLAUDE.md` and `GOALS.md`
Either ask Claude to interview you (*"read `05 Skills/setup.md` and set me up"*), or edit the files by hand using the templates in the appendix below.

### 4. Theme the Project Template (optional)
Open **`03 Projects/(PROJECT TEMPLATE)`** as its own Obsidian vault and customize appearance, theme, and plugins. Every project you duplicate from it inherits the same setup — configure once.

---

## 📎 Bonus setups (optional, later)

### 📱 Use it from your phone *(experimental — feature names may change)*
Claude can be used beyond the terminal, including desktop/web apps that can point at this vault folder. Those app and feature names move fast, so check the official docs for the current options rather than relying on step names here: <https://code.claude.com/docs/en/overview>. The idea: point Claude at your existing vault folder (e.g. `~/Desktop/[YOUR VAULT NAME]`) as its workspace, and turn on notifications so you can capture ideas from anywhere.

### 👥 Sync across devices / share with a team
Use [**Obsidian Sync**](https://obsidian.md/sync): **Settings → Core Plugins → Sync → On**, pick a remote vault, and invite collaborators by their Obsidian email. *(Tip: sync all file types.)*

---

## 🧾 Templates (copy-paste, for building by hand)

### 📄 `CLAUDE.md`

~~~markdown
# [Vault Name] — Claude Context

> [One sentence: what this vault is and who it serves.]

## Who I Am & My Purpose
[2–3 paragraphs, first person. What you do, your purpose, what energizes you,
what you refuse to do, plus personal context (faith, family, health, location).]

## Claude's Purpose Here
- [responsibility 1]
- [responsibility 2]
**Prime directive:** [the single most important thing Claude should do well].

## Rules & Boundaries
- **Communicate [blunt / supportive / balanced].**
- **Prefix AI-created notes with `(C)`.**
- **Ask before editing a note I created** — propose, then wait.
- **Wiki-link related notes** with `[[note name]]`.
- **Skills live in `05 Skills/` as markdown.**
- [Your own hard rules.]

## Folder Structure
[The 00–05 tree.]

## My Strengths & Weaknesses
**Strengths:** …
**Weaknesses & blind spots:** …

## My Goals & Current Progress
[Main goal with a number + date, where you are today, the plan, risks.]

## Weekly Update
> **Last updated:** _[each week]_
- What's working:
- What's not working:
- What I'm sitting on / need to decide:
- Deadlines / time-sensitive:

## My Current Projects
_No projects yet._
~~~

### 🎯 `GOALS.md`

~~~markdown
# Goals
## The Target
- [Your #1 concrete goal — with a number and a date.]
## Why it matters
- [The real reason. What winning unlocks.]
## The Plan
- [Rough step-by-step from today → the goal.]
## Where I am today
- [Current numbers / progress / runway.]
## Risks & time-sensitive
- [Anything that could derail this, or has a deadline.]
~~~

### 🗂️ Project `CLAUDE.md`

~~~markdown
# [Project Name]
[One paragraph: what this project is and who it's for.]

## Claude's Role
[The actual job — be specific.]
**Prime directive:** If a session drifts without moving toward [shipped output], nudge me back.

## Process
1. `00 Ideas/` — capture
2. `01 In Progress/` — build
3. `02 Done/` — shipped

## Rules & Conventions
- **`(C)` prefix** for AI-created content notes.
- **Ask before editing** files you didn't create.

## Current Status
> **Last updated:** [date] · **Status:** Just created.
~~~

---

## 🙏 Credits

This setup is a personal adaptation of the **AI Second Brain** template concept, built on top of the open-source **[Claudian](https://github.com/YishenTu/claudian)** Obsidian plugin. Huge thanks to the original creators — I just made it my own. You should too. 🧠✨
