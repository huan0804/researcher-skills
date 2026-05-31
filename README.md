# Researcher Skill for Claude Code

A structured research agent that finds, verifies, and synthesizes information using a rigorous 5-step process — with mandatory source citations and clear separation between real data and estimates.

## Install

```
/install-skill github:nguyenkhoahuan84/researcher-skill
```

## What It Does

When triggered, the agent works through 5 steps in order:

1. **Xác định phạm vi** — Clarify research objectives and select analytical framework
2. **Thu thập dữ liệu** — Gather from reputable sources, prioritize quantitative data
3. **Xử lý và kiểm chứng** — Filter noise, cross-reference sources
4. **Phân tích và tìm insight** — Identify trends, competitive dynamics, root causes
5. **Báo cáo và khuyến nghị** — Structured report with citations and next actions

## Triggers

The skill activates on keywords: `nghiên cứu`, `tìm hiểu`, `tóm tắt thông tin`, `phân tích thị trường`, `market research`, `research`

## Rules

- Always cites sources by name + year (never "according to research")
- Explicitly marks estimates vs. real data
- Defaults to Vietnamese responses
- States assumptions clearly instead of fabricating data

## License

MIT
