# Skill Ideation 💡

**Stop brainstorming generic skill ideas. Find the ones that actually matter.**

"Time Management" isn't a skill — it's a category. "Communication" means everything and helps nothing. This Agent Skill generates *specific*, *actionable* skill ideas that fill real gaps.

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## The Problem

Most brainstorming produces:
- Generic topics (Time Management, Communication)
- Things Google already answers well
- Ideas too broad to be useful

**This skill flips the approach:** Problem-first, not category-first.

---

## Installation

### npx skills
```bash
npx skills add git@github.com:mcltyl/skill-ideation.git
```

### Claude Code / Codex CLI
```bash
git clone https://github.com/mcltyl/skill-ideation.git ~/.claude/skills/skill-ideation
```

### OpenClaw
```bash
git clone https://github.com/mcltyl/skill-ideation.git ~/.openclaw/skills/skill-ideation
```

---

## Skills

| Skill | Description |
|-------|-------------|
| [skill-ideation](skills/skill-ideation) | Problem-driven skill idea generation |

---

## What Makes a Good Skill Idea?

| ❌ Bad | ✅ Good | Why |
|--------|---------|-----|
| Time Management | deadline-panic-recovery | Specific moment |
| Communication | saying-no-to-boss | Clear situation |
| Leadership | first-week-as-manager | Time-bound, universal |
| Productivity | procrastination-shame-spiral | Addresses real pattern |

---

## Generation Methods

### 1. From Failure
What do people consistently screw up?
- first-apology-attempt
- feedback-delivery-fail

### 2. From Moments
What 10-minute window needs help?
- waiting-for-interview
- receiving-bad-news

### 3. From "Nobody Taught Me"
What did school skip?
- how-to-negotiate-rent
- when-to-quit

### 4. From Verbs
- Not "communication" → "saying no"
- Not "relationships" → "after the argument"

### 5. From Contrarian
What sounds wrong but is right?
- laziness-as-wisdom
- quitting-as-skill

---

## Example Output

**Prompt:** "Give me skill ideas about anxiety"

| Idea | One-Liner | Type |
|------|-----------|------|
| 3am-thought-spiral | What to do when your brain won't stop | 🛠️ Practice |
| anxiety-vs-intuition | Is this fear or wisdom? | 🧠 Mindset |
| anxiety-at-parties | Surviving events when you'd rather hide | 🛠️ Practice |
| explaining-anxiety | How to tell someone who doesn't get it | 🛠️ Practice |

---

## Quality Filters

| Test | Question |
|------|----------|
| **Who** | Specific person who needs this? |
| **When** | Clear trigger moment? |
| **Gap** | Google doesn't answer well? |
| **Teachable** | Can be conveyed in text? |
| **Timeless** | Still useful next year? |

---

## Commands

```
"Give me skill ideas about [topic]"
"Brainstorm skills for [situation]"
"What skills could help people who [problem]?"
"I want to create a skill for [moment]"
```

---

## License

MIT

---

## Support

If this helps you create valuable skills:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
