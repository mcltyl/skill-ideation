# Skill Ideation 💡

**Stop brainstorming generic skill ideas. Start finding the ones that actually matter.**

Ever tried to brainstorm skill ideas and ended up with a list of vague topics like "Time Management" or "Communication"? Those aren't skills — they're categories. This Agent Skill helps you find *specific*, *actionable* skill ideas that fill real gaps.

This skill follows the [Agent Skills specification](https://agentskills.io/specification).

Works with Claude Code, Codex CLI, OpenClaw, and any Agent Skills-compatible tool.

---

## The Problem

Coming up with skill ideas is easy. Coming up with **good** skill ideas is hard.

Most brainstorming produces:
- Generic topics (Time Management, Communication Skills)
- Things Google already answers well
- Ideas too broad to be useful

**This skill flips the approach: problem-first, not category-first.**

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
| [skill-ideation](skills/skill-ideation) | Structured brainstorming framework with 560 categories and 8150+ ideas |

---

## What's Inside

### 🧭 First-Principles Framework

Instead of listing categories, we start with questions:
- What do people consistently get wrong?
- What "obvious" thing isn't obvious?
- What do you explain to others repeatedly?
- What took you years to figure out?

### 📦 560 Category Prompts (8150+ Ideas)

Each category includes 15 specific, actionable ideas:

| Domain | Categories |
|--------|------------|
| **Life Moments** | Micro-Moments, Life Logistics, Identity Transitions |
| **Psychology** | Personality Patterns, Money Psychology, Social Anxiety |
| **Philosophy** | Stoicism, Existentialism, Buddhism/Zen, Taoism, Ethics |
| **Inner Work** | Shadow Work, Inner Child, Attachment Theory, Forgiveness |
| **Relationships** | Dating, Long-Term, Family, Friendship, Workplace |
| **Career** | Job Search, Career Change, Upward Management, Remote Work |
| **Creativity** | Creative Process, Writing, Design, Music, Photography |
| **Health** | Mental Health, Fitness, Nutrition, Sleep, Chronic Illness |
| **Tech** | Coding, AI/ML, Cloud, Cybersecurity, No-Code, Terminal |
| **Business** | Startup, Freelancing, Sales, Marketing, Operations |
| **Finance** | Budgeting, Investing, Tax, Retirement, Wealth Building |
| **Special Seasons** | New Job, Marriage, Parenting, Retirement, Grief, Coming Out |
| **Big Projects** | Writing a Book, Running a Marathon, Building a Home |

**Sample from "Micro-Moments" category:**

| Idea | One-Liner | Type |
|------|-----------|------|
| first-week-fired | 剛被開除的那一週 | 🧠 Coping |
| receiving-bad-news | 接收壞消息的那一刻 | 🛠️ Practice |
| 3am-thoughts | 凌晨三點的想法 | 🧠 Mindset |
| job-offer-decision | 收到 offer 的抉擇 | 🛠️ Framework |
| breakup-moment | 分手的那一刻 | 🧠 Coping |

### 🔧 5 Generation Techniques

1. **From Failure** — What do people consistently screw up?
2. **From Moments** — What 10-minute window needs help?
3. **From "Nobody Taught Me"** — School skipped this
4. **From Verbs** — Not "communication" but "saying no"
5. **From Contrarian** — What sounds wrong but is right?

### 🎯 User-Direction Following

**The core principle:** User gives a seed, agent diverges.

When you say "brainstorm about swimming", it doesn't say "swimming isn't in my categories." It goes:
- Swimming fear (psychological barrier)
- Swimming + meditation (the zen of laps)
- Pool etiquette (unwritten rules)
- Open water (ocean swimming, triathlons)
- Teaching kids to swim
- Swimming across cultures

**You lead. It follows and expands.**

---

## Quality Filters

The skill includes quality tests for every idea:

| Test | Question |
|------|----------|
| **Who** | Specific person who needs this? |
| **When** | Clear trigger moment? |
| **Gap** | Google doesn't answer well? |
| **Teachable** | Can be conveyed in text? |
| **Timeless** | Still useful next year? |
| **Narrow-Universal** | Specific but common? |

### Naming Matters

| ❌ Bad | ✅ Good | Why |
|--------|---------|-----|
| time-management | deadline-panic-recovery | Situation-specific |
| communication | saying-no | Action-specific |
| relationships | after-the-argument | Moment-specific |

---

## Example Usage

**Prompt:**
```
Generate skill ideas for 30-year-old anxiety
```

**Output:**
| Idea | One-Liner | Type |
|------|-----------|------|
| quarter-life-audit | 25-35: Am I on track? | 🧠 Framework |
| 30-unmarried | The pressure nobody admits | 🧠 Psychology |
| 30-career-switch | Is it too late? (No.) | 💡 Permission |
| 30-savings-reality | What "should" you have? | 🛠️ Practical |
| 30-friendships | Why everyone disappeared | 🧠 Psychology |
| 30-vs-20 | The mindset shift | 💡 Reflection |
| 30-parents-aging | They're getting old | 🧠 Preparation |

**Prompt:**
```
I want to build skills around the emotion of "envy"
```

**Output:**
| Idea | One-Liner | Type |
|------|-----------|------|
| envy-signal | 羨慕是指路牌 | 💡 Reframe |
| social-media-envy | 為什麼別人過得比我好 | 🧠 Psychology |
| colleague-envy | 同事升遷我沒有 | 🧠 Processing |
| envy-to-action | 把羨慕轉成行動 | 🛠️ Practice |
| envy-confession | 承認羨慕的勇氣 | 🧠 Self-awareness |

---

## Full Category List

<details>
<summary>Click to expand all 560 categories</summary>

### Life & Personal Growth (1-50)
Micro-Moments, Micro-Skills, Identity Transitions, Personality Patterns, Abstract Concepts, Life Logistics, Contrarian Wisdom, Philosophy & Mortality, Body Wisdom, Time Experience, Money Psychology, Space & Environment, Creativity & Expression, LGBTQ+ Experience, Immigration & Expat, Startup Life, Social Anxiety, Travel & Movement, Parenting & Family, Geopolitics & Global Awareness, Spiritual Seeking, Professional Skills, Fashion & Style, Food & Cooking, Digital Life, Pet Ownership, Sports & Competition, Side Hustles, Volunteer & Service, Nature & Outdoors, Humor & Comedy, Aging Well, Gaming & Play, Collecting, DIY & Crafts, Learning & Education, Books & Literature, Film & TV, Podcast & Audio, Writing & Publishing, Public Speaking, Negotiation & Influence, Leadership & Management, Teamwork & Collaboration, Customer Service, Sales & Persuasion, Marketing & Branding, Finance & Investing, Legal Literacy, Health & Wellness

### Relationships & Emotional Intelligence (51-100)
Dating, Long-Term Relationships, Breakups, Friendship, Family Dynamics, Conflict Resolution, Apologies, Boundaries, Vulnerability, Trust, Jealousy, Loneliness, Gratitude, Forgiveness, Empathy, Active Listening, Difficult Conversations, Emotional Regulation, Self-Compassion, Self-Awareness, Mindfulness, Meditation, Stress Management, Anxiety Management, Depression Coping, Trauma Healing, Grief Processing, Anger Management, Fear Facing, Joy Cultivation, Hope Building, Patience Practice, Resilience Building, Self-Esteem, Body Image, Perfectionism, People Pleasing, Procrastination, Decision Making, Goal Setting, Habit Formation, Motivation, Discipline, Focus, Time Management, Energy Management, Sleep Optimization, Work-Life Balance, Burnout Recovery, Career Planning

### Professional & Career (101-200)
Job Search, Resume Writing, Interview Skills, Salary Negotiation, First Job, Career Pivot, Promotion Strategy, Performance Reviews, Workplace Politics, Managing Up, Peer Relationships, Mentorship, Networking, Personal Branding, LinkedIn Strategy, Remote Work, Hybrid Work, Freelancing, Consulting, Entrepreneurship, Product Management, Project Management, Engineering, Design, Data Science, Marketing, Sales, Finance, HR, Legal, Operations, Strategy, Leadership, Team Building, Hiring, Firing, Feedback, Delegation, Meeting Management, Email Communication, Presentation Skills, Stakeholder Management, Cross-functional Work, Global Teams, Startup Culture, Corporate Culture, Agency Life, Non-profit, Government, Academia

### Technology & Digital (201-300)
... (categories 201-300)

### Health & Wellness (301-400)
... (categories 301-400)

### Philosophy & Inner Work (401-510)
... (categories 401-510)

### Special Seasons & Transitions (511-560)
Starting New Job, Getting Married, Becoming Parent, Moving to New City, Starting College, Retirement Transition, Career Change, Divorce Navigation, Grief and Loss, Health Crisis, Financial Crisis, Midlife Transition, Quarter-Life Crisis, Returning to Work, Relocation Abroad, Addiction Recovery, Coming Out, Aging Parents Care, Empty Nest, Launching Business, Legacy Project, Writing a Book, Running a Marathon, Learning New Language, Building Dream Home, Planning Wedding, Sabbatical, Gap Year, Digital Detox, Minimalist Journey

</details>

---

## Stats

| Metric | Value |
|--------|-------|
| Categories | 560 |
| Ideas | 8150+ |
| Lines of Content | 13,300+ |
| Last Updated | 2026-03-24 |

---

## License

MIT

---

## Support

If this helps you create valuable skills:

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-support-yellow?style=flat&logo=buy-me-a-coffee)](https://buymeacoffee.com/mclty)
