# 🧠 Second Brain by Ea

**Your ready-to-go AI second brain** — an [Obsidian](https://obsidian.md) vault that Claude lives inside, reads for context, and personalizes *for* you. Store everything in one place; get a thinking partner that already knows who you are and what you're working toward.

> Setup is mostly clicks + **one** copy-paste line. Once it's running, you type **`set this up`** and Claude interviews you and builds the rest.

---

## What you'll need

- **[Obsidian](https://obsidian.md)** — a free notes app. This vault is just a folder of plain-text files it opens. *(Mac or Windows, desktop.)*
- **A paid Claude plan** — Pro, Max, Team, or Enterprise → [claude.com/pricing](https://claude.com/pricing). *(The free Claude.ai plan can't run Claude Code, which powers this.)*

---

## Set up — 5 steps (~10 minutes)

### 1. Download this vault
On this GitHub page, click the green **`Code`** button → **`Download ZIP`**. Then **double-click the `.zip` to unzip it.** You'll get a folder (it may be named something like `…-main` — that's fine, rename it to anything you like, e.g. `My Second Brain`).

### 2. Install Claude Code + log in — *the one command you'll type*
Claude works inside Obsidian through a **free-to-install** tool called **Claude Code** — it needs your paid Claude plan to actually run. Open your terminal and paste **one** line:

- **Mac** — open **Terminal** (`⌘ + Space`, type "Terminal", Enter):
  ```bash
  curl -fsSL https://claude.ai/install.sh | bash
  ```
- **Windows** — open **PowerShell** (Start menu → type "PowerShell"):
  ```powershell
  irm https://claude.ai/install.ps1 | iex
  ```

When it finishes, **close the terminal window and open a new one** (this loads Claude Code — otherwise the next command says "command not found"). Then type **`claude`** and press Enter. It'll ask a couple of quick questions — choose **"Log in with your Claude account"** (not the API-key option), accept the defaults, and finish logging in when the browser opens.

> 💡 **Log in with a _paid_ plan.** A free Claude account signs in fine but Claude Code won't run — grab a plan at [claude.com/pricing](https://claude.com/pricing) first.

That's it — you normally won't need the terminal again. *(Never used a terminal? Full walkthrough: <https://code.claude.com/docs/en/quickstart>)*

### 3. Open the vault in Obsidian
Install **[Obsidian](https://obsidian.md)**, open it → **"Open folder as vault"** → pick the folder you unzipped in Step 1. When it opens, click the note **`👋 START HERE`**.

### 4. Install the Claudian plugin
This puts Claude in a panel right beside your notes.
1. Obsidian **Settings** (gear icon, bottom-left) → **Community plugins**.
2. If you see a **"Turn on community plugins"** button, click it **first**.
3. Click **Browse**, search **`Claudian`**, click **Install**, then **Enable**.

*(Claudian is the open-source plugin that connects Obsidian to the Claude Code you installed in Step 2. Repo: <https://github.com/YishenTu/claudian>)*

### 5. Type `set this up`
Open the **Claudian panel** (the Claude icon on the right sidebar) and type:

```
set this up
```

Claude asks you a few questions (~5 min) and builds and personalizes your whole second brain. 🎉

---

## Stuck?

| Problem | Fix |
|---|---|
| The Community plugins section looks locked | Click **"Turn on community plugins"** first (Step 4). |
| Obsidian won't open the folder | Make sure you **unzipped** the `.zip` first (Step 1). |
| Where do I actually type? | The **Claudian panel** on the right of Obsidian — click the Claude icon. |
| "Not logged in" / it won't respond | Run `claude` in your terminal once and log in (Step 2). You need a **paid** Claude plan. |
| Nothing happened when I typed `set this up` | Type **`read CLAUDE.md and set this up`** instead. |

---

## Want the details?

- The **manual / advanced** path, the full philosophy, and bonus setups (use it from your phone, sync across devices) live in **[`docs/manual-setup.md`](docs/manual-setup.md)**.
- Built on the open-source **[Claudian](https://github.com/YishenTu/claudian)** plugin and the AI Second Brain concept. Copy it, make it yours. 🧠✨
