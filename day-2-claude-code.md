# Day 2 Practice Plan: Understanding a Codebase with Claude Code

**Date:** 2026-06-27
**Goal:** Get comfortable asking Claude to read and explain code — no editing today.

---

## Schedule (1 hour)

### 0:00 – 0:10 | Warm-up
- Open your `claude-practice` folder in the terminal and launch Claude Code
- Run `/help` to browse available commands
- Ask: *"What files are in this folder and what do they contain?"*

### 0:10 – 0:25 | Explore a Real Project
- Navigate to any existing project on your machine (even a small one)
- Ask Claude: *"What does this project do?"*
- Ask Claude: *"Explain the folder structure to me"*
- Just read — no changes yet

### 0:25 – 0:40 | Go Deeper
- Pick one file from that project and ask: *"Walk me through what this file does, step by step"*
- Ask a follow-up: *"What would break if I deleted this file?"*
- Try: *"Are there any obvious improvements you'd suggest here?"* (read only — don't apply them)

### 0:40 – 0:50 | Practice Prompting
- Ask the same question two different ways and compare the answers
  - Vague: *"Explain this code"*
  - Specific: *"Explain what this function does and why it might fail"*
- Note which style gives more useful output

### 0:50 – 1:00 | Reflect & Log
- Add 3 bullet points to `notes.md` summarizing what you learned today
- Write down one question you still have — ask Claude to answer it

---

## Key Commands to Practice Today

| Command | What it does |
|---|---|
| `/help` | Lists all available slash commands |
| `/clear` | Clears the conversation context |
| `! git status` | Check repo state without leaving Claude |
| `! cat filename` | Print a file to the terminal |

---

*Today is about reading, not writing. The more you understand before editing, the fewer mistakes you make.*

---

## My Notes

1. cd means change folder.
2. pwd shows current folder.
3. ls shows files in current folder.

---

## Mistakes I Should Avoid Tomorrow

1. **Don't ask vague questions** — Instead of "explain this code," say "explain what this function does and when it might fail." Specific prompts get specific answers.
2. **Don't edit files before understanding them** — Always ask Claude to explain a file first. Changing code you don't understand is how bugs get introduced.
3. **Don't forget to use `/clear` between unrelated tasks** — Carrying old context into a new question can confuse Claude and lead to off-target answers.
