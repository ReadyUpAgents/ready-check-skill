# ready-check-skill

An agent skill for [Ready Check](https://readyupagents.com/ready-check/), the prepaid ReadyUpAgents API that inspects one inbound email and returns structured findings (kind, verdict, scores, named checks). It never writes a reply, connects to an inbox, or sends mail.

The skill is a single Markdown file with no scripts: [skills/ready-check/SKILL.md](skills/ready-check/SKILL.md). It tells an agent when Ready Check fits and how to call it through the MCP server ([ready-check-mcp](https://github.com/ReadyUpAgents/ready-check-mcp)) or the HTTP API.

## Install

```bash
npx skills add ReadyUpAgents/ready-check-skill
```

## Pricing

$0.0025 per standard check. Packs: $1 = 400 checks, $5 = 2,000 checks. Unused credit never expires while the key stays open.

## Links

- Facts: https://readyupagents.com/ready-check/
- OpenAPI: https://readyupagents.com/openapi.yaml
- MCP Registry: `io.github.ReadyUpAgents/ready-check`
- Terms: https://readyupagents.com/terms/
- Privacy: https://readyupagents.com/privacy/

## License

MIT © ReadyUpAgents
