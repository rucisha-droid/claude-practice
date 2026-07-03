# Daily Study Plan: Learning Claude Code & Codex

## Week 1 — Getting Comfortable with the Tools

### Day 1: Setup & First Steps
- Install Claude Code (`npm install -g @anthropic-ai/claude-code`)
- Authenticate and launch in a practice folder
- Run your first prompt: ask Claude to explain a simple file
- Practice: `git status`, `git log`, `/help`, `/clear`

### Day 2: Understanding a Codebase
- Open a real or sample project
- Ask Claude: "what does this project do?"
- Ask Claude: "explain the folder structure"
- Practice reading before editing — no changes today

### Day 3: Making Your First Edits
- Create a simple Python or JavaScript file with Claude
- Ask Claude to add a feature to it
- Review the diff with `! git diff` before accepting
- Undo and redo using `! git checkout .`

### Day 4: Introduction to Codex
- Sign in to OpenAI and explore Codex (codex.com or API)
- Run a simple code generation prompt
- Compare output style between Claude Code and Codex
- Note: what did each do better?

### Day 5: Fixing Bugs
- Intentionally introduce a bug in your practice file
- Ask Claude Code to find and fix it
- Do the same with Codex
- Compare how each tool explains the fix

### Day 6: Review & Practice
- Revisit Days 1–5 concepts
- Try a mini project: a to-do list script using Claude Code
- Ask Claude to write tests for the script

### Day 7: Rest & Reflect
- Write 3 things you learned this week
- Note what confused you — ask Claude to explain it

---

## Week 2 — Building Real Skills

### Day 8: Working with Git + Claude
- Create a new branch: `! git checkout -b feature/test`
- Let Claude make changes on that branch
- Merge it back and review the history

### Day 9: Multi-file Projects
- Ask Claude to scaffold a small project (e.g. a weather CLI app)
- Explore how Claude handles multiple files at once
- Ask: "what files did you create and why?"

### Day 10: Codex for Code Completion
- Use Codex to autocomplete functions
- Practice writing partial code and letting Codex complete it
- Try different prompt styles: detailed vs. vague

### Day 11: Refactoring Practice
- Take messy code (or ask Claude to generate some)
- Ask Claude: "refactor this to be cleaner"
- Compare before and after with `! git diff`

### Day 12: Writing Tests
- Ask Claude to write unit tests for a function you made
- Run the tests in terminal
- Ask Claude to fix any failing tests

### Day 13: Security & Code Review
- Ask Claude: "review this code for security issues"
- Try the `/code-review` skill
- Practice reading Claude's suggestions critically

### Day 14: Weekly Review
- Build one small complete project using Claude Code
- Document what you built in a README.md (ask Claude to help)
- Reflect: Claude Code vs Codex — when to use which?

---

## Quick Reference

| Tool | Best For |
|---|---|
| Claude Code | Full project editing, explanation, debugging, review |
| Codex | Fast code generation, autocomplete, snippets |

## Daily Habit (10 min/day)
1. Open your practice folder
2. Run one prompt you've never tried before
3. Review what Claude or Codex produced
4. Ask one follow-up question

---

*Start small. Stay consistent. The tools get more powerful as you learn to prompt better.*
