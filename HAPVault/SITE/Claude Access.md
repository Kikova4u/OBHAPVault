# 🤖 Claude Access Instructions

**How Claude reads this vault**

---

## Via Claude.ai (this chat)

1. Push vault to GitHub (see setup below)
2. At the start of any session, paste this into chat:
    
    > "Fetch my HAP vault index: [raw GitHub URL]/HAP-INDEX.md"
    
3. Claude fetches it instantly — full site context loaded in seconds
4. For specific data: "Fetch my affiliate tracker" → Claude reads AFFILIATE/AFFILIATE-TRACKER.md

**GitHub raw URL format:**

```
https://raw.githubusercontent.com/[username]/HAPVault/main/HAP-INDEX.md
```

---

## Via Claude Code (local)

Claude Code runs on your machine and reads this vault directly. Point it to the vault folder path:

```
/path/to/HAPVault/
```

No GitHub needed — Claude Code reads `.md` files natively.

---

## Via OpenClaw (future)

Once OpenClaw is deployed on DigitalOcean VPS:

1. Mount the vault via GitHub sync
2. OpenClaw reads all `.md` files as its knowledge base
3. Every session starts with full HAP context — no manual loading

---

## GitHub Setup (one-time, 10 minutes)

1. Create free account at github.com
2. Create new repo: `HAPVault` (private recommended)
3. In terminal: `cd /path/to/HAPVault && git init && git remote add origin [repo URL]`
4. `git add . && git commit -m "Initial vault" && git push`
5. Enable GitHub Obsidian sync plugin OR use Git plugin in Obsidian
6. From now on: every save syncs to GitHub automatically

---

## What to Tell Claude at Session Start

Paste this at the start of every Claude.ai session:

```
My HAP vault is at: https://raw.githubusercontent.com/[username]/HAPVault/main/
Fetch HAP-INDEX.md to load my site context.
```

Claude will fetch the index, see all article statuses, links, and pending actions — and be fully briefed in under 10 seconds.