# Daily spiritual reflection skill

A reusable agent skill for writing a daily Catholic contemplative reflection: one verified passage from the Carmelite or monastic tradition, tied to the day's Mass readings, with a short practice and checked further-reading links. Then it's delivered by chat or email, with a no-repeat log.

This is the pipeline behind "Carmel daily pick", the daily reflection Niels Pacheco-Barrios's assistant writes each morning.

## Use it
- **Claude Code / Claude skills**: copy `SKILL.md` into `~/.claude/skills/daily-spiritual-reflection/` (or a project's `.claude/skills/`).
- **Any agent**: paste `SKILL.md` into its system prompt or task.
- **Daily automation**: run it on a schedule (cron, a scheduled agent, or a routine) at around 6:40 AM local time.

## Tools it needs
- Web search and page fetch (any deep-research or search tool: Exa, Perplexity, Parallel, Firecrawl, or built-in web search).
- An email-sending tool (e.g. the Gmail API or a Gmail MCP), if you deliver by email.
- A persistent log (a text file, database, or agent memory) so picks never repeat.

The key design choices are: anchor every pick in the day's liturgy, quote only text opened and verified verbatim, open every link before citing it, and keep each one to one passage, one idea, and one practice.
