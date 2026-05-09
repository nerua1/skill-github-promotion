---

description: Complete playbook for promoting GitHub repos — platform selection, hook writing, social preview design, content calendar, and Reddit/HN/Dev.to tactics.
type: reference
created: 2026-04-18
authors: [nerua1]
version: "1.0.0"
---

# GitHub Promotion Skill 🚀

## Quick Start

1. Write self-explanatory description (benefit-first, max 90 chars)
2. Generate 1280×640 social preview image (Arena.ai)
3. Post on Hacker News "Show HN" or Reddit r/LocalLLaMA
4. Monitor with F5Bot, respond to feedback

---

## Platform Matrix

| Platform | Best For | When to Post | Audience |
|----------|----------|--------------|----------|
| **Hacker News** | Tool launches | Tue-Thu 9-11am ET | Senior devs, founders |
| **Product Hunt** | Productized tools | Tuesday (least noise) | Early adopters |
| **Reddit r/LocalLLaMA** | Local AI setups | Anytime | LLM tinkerers |
| **Reddit r/selfhosted** | Privacy-focused tools | Anytime | Homelabbers |
| **Reddit r/ClaudeAI** | Claude skills | Weekends | Power users |
| **Dev.to** | Tutorials | Anytime | Developers, learners |
| **Indie Hackers** | Building in public | Anytime | Bootstrappers |

### Subreddits to Target

- r/LocalLLaMA — local models, LM Studio, RAM optimization
- r/selfhosted — multi-agent, privacy, no cloud
- r/ClaudeAI — Claude Code skills, prompts
- r/artificial — general AI news
- r/webdev — Showoff Saturday (only day self-promo allowed)
- r/SaaS — if monetizing
- r/sideproject — indie projects

---

## Hook Writing Rules

### Formula
```
[Problem] + [Outcome] + [Time/Number]
```

### Examples
- ❌ "ACP skill for cross-agent messaging via JSON-RPC"
- ✅ "4 agents. 1 chat. 0 friction."

- ❌ "Iterative code improvement pipeline with LLM"
- ✅ "Write → Review → Fix → Ship"

### Checklist
- [ ] Starts with benefit (not technology)
- [ ] Max 8 words
- [ ] Contains a number if possible
- [ ] No jargon (MCP, ACP, JSON-RPC — only in body)
- [ ] Action-oriented verb

---

## Social Preview Images

### Specs
- **Size**: 1280 × 640 px
- **Format**: PNG or JPG
- **File**: `< 1MB`

### Layout (Arena.ai prompt template)
```
1280x640 social preview card. Dark gradient from deep purple to navy.
LEFT (60%): Large white title "[REPO NAME]" + gray subtitle "[HOOK]".
RIGHT (40%): Circular profile photo, white border + small agent icons.
Bottom-left: "AI agent skill". Bottom-right: "github.com/nerua1/[repo]".
Style: Minimal, dark mode, cyberpunk-lite. High contrast.
```

### Hooks by Repo

| Repo | Hook |
|------|------|
| acp-bridge | "4 agents. 1 chat. 0 friction." |
| shared-memory-stack | "Your agents remember everything." |
| ralph-wiggum-loop | "Write → Review → Fix → Ship" |
| openclaw-setup-guide | "From zero to multi-agent in 30 min." |
| god-mode-skill | "When Claude says no, I say yes." |
| arena-council-skill | "3 models vote. You win." |
| skill-vetter | "Scan before you install." |

---

## Content Calendar (4 weeks)

| Week | Platform | Topic | Repo |
|------|----------|-------|------|
| 1 | Dev.to | "3 AI agents on Mac Mini: RAM lessons" | ram-orchestrator, setup-guide |
| 1 | r/LocalLLaMA | "Patched Hermes for LM Studio custom providers" | hermes PR |
| 2 | HN | "Show HN: ACP bridge for Claude/Hermes/OpenClaw" | acp-bridge |
| 2 | r/selfhosted | "Multi-agent shared memory with Obsidian" | shared-memory-stack |
| 3 | Product Hunt | Launch acp-bridge skill pack | acp-bridge |
| 3 | Dev.to | "How Claude and Hermes negotiate RAM via ACP" | ram-orchestrator |
| 4 | r/ClaudeAI | "Skill: shared memory for Claude Code" | shared-memory-stack |

---

## F5Bot Keywords

Set up free alerts at https://f5bot.com for:
- "multi-agent"
- "Claude Code skill"
- "OpenClaw"
- "local LLM Mac"
- "Hermes agent"
- "LM Studio setup"

Reply helpfully, drop repo link only if directly relevant.

---

## GitHub Profile README Checklist

- [ ] Hook sentence at top
- [ ] Pinned repos (max 6, best first)
- [ ] Tech stack badges
- [ ] PayPal link
- [ ] Dev.to / blog link
- [ ] Social preview images on all pinned repos

---

## Submission to Awesome Lists

Target lists for PRs:
- awesome-ai-agents
- awesome-claude
- awesome-local-llm
- awesome-mcp
- awesome-openclaw (if exists)

Format: `[repo-name](url) — one-line description.`

---

If this saved you time: [☕ PayPal.me/nerudek](https://www.paypal.me/nerudek)
