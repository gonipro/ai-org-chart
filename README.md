# ai-org-chart · Build an org chart for your AI team

**English** | [한국어](README.ko.md) | [日本語](README.ja.md) | [简体中文](README.zh-CN.md)

Once you have more than ten AI windows open, nobody knows who does what, and you end up playing team lead, so work stalls.
Split those windows **like a small company**: each window does only its own job, and you just say OK.

### Try it without installing
Paste the text in [PROMPT.md](PROMPT.md) into the AI you already use (Claude, ChatGPT, Gemini). It asks you a few questions, one at a time, and draws the org chart.

### Use it as a Claude Code skill
Tell Claude:
> "Install skills/ai-org-chart from github.com/gonipro/ai-org-chart into my skills (~/.claude/skills) and build my AI org chart."

### The 10 steps
1. List every task you repeat each week
2. Pick how to split: by brand/channel, by kind of work (planning, writing, design), or both
3. One seat = one window (one line for its job, one line for what it does NOT do)
4. More than 10 windows? Add a **coordinator** seat (assigns work, follows up, reviews)
5. Work several teams share goes to **shared seats** (ads, research, development)
6. Decide what **only you approve** (publishing, payments, deploys, messages to customers)
7. One **progress board** (idea → plan → draft → scheduled → published)
8. One place where windows talk, one place where decisions are written down
9. Three lines of instructions per seat (job / not my job / how to report)
10. Draw the org chart on one page

### Example (fictional company)
```
Owner (human)
 └ Coordinator ── assigns work · reviews · brings decisions to the owner
    ├ Brand A team: planning · writing · design · video
    ├ Brand B team: writing · design
    └ Shared: ads · research · development
```

Made by [GoniPro](https://gonipro.app) · MIT
