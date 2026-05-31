# Researcher Skill

A structured research agent that finds, verifies, and synthesizes information using a rigorous 5-step process — with mandatory source citations and clear separation between real data and estimates.

Works with Claude Code, Cursor, Windsurf, GitHub Copilot, and any AI tool that accepts a system prompt.

---

## Installation by Platform

### Claude Code
```
/install-skill github:huan0804/researcher-skills
```

### Cursor
Copy `.cursorrules` to your project root, or add to global Cursor rules in Settings → Rules for AI.

### Windsurf
Copy `.windsurfrules` to your project root.

### GitHub Copilot
Copy `.github/copilot-instructions.md` to your repo's `.github/` folder.

### ChatGPT / Gemini / Grok / Any AI
Open `system-prompt.md`, copy the full content, and paste it into the system prompt or custom instructions field of your AI tool.

---

## What It Does

When triggered, the agent works through 5 steps in order:

1. **Xác định phạm vi** — Clarify research objectives and select analytical framework
2. **Thu thập dữ liệu** — Gather from reputable sources, prioritize quantitative data
3. **Xử lý và kiểm chứng** — Filter noise, cross-reference sources
4. **Phân tích và tìm insight** — Identify trends, competitive dynamics, root causes
5. **Báo cáo và khuyến nghị** — Structured report with citations and next actions

---

## Rules

- Always cites sources by name + year (never "according to research")
- Explicitly marks estimates vs. real data
- Defaults to Vietnamese responses
- States assumptions clearly instead of fabricating data
- No padding — every sentence must carry information

---

## File Structure

```
researcher-skills/
├── SKILL.md                        ← Claude Code
├── .cursorrules                    ← Cursor
├── .windsurfrules                  ← Windsurf
├── .github/copilot-instructions.md ← GitHub Copilot
├── system-prompt.md                ← Copy-paste for any AI
├── package.json
├── LICENSE
└── README.md
```

---

## License

MIT © huan0804
