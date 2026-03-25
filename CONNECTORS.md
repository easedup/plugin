# Connectors

## How tool references work

Plugin files use `~~category` as a placeholder for whatever tool the user connects in that category. For example, `~~curriculum` might mean the Australian Curriculum v9 server, Common Core, or any other curriculum MCP server.

Plugins are **tool-agnostic** — they describe workflows in terms of categories (curriculum standards, LMS, etc.) rather than specific products. The `.mcp.json` pre-configures specific MCP servers, but any MCP server in that category works.

## Connectors for this plugin

| Category | Placeholder | Included servers | Other options |
|---|---|---|---|
| Curriculum standards | `~~curriculum` | EasedUP ACv9, EasedUP Common Core, EasedUP UK National Curriculum | Any curriculum MCP server |

## About the curriculum servers

All three included servers are published by [EasedUP](https://easedup.com) and provide structured access to official curriculum frameworks:

| Server | Curriculum | Coverage |
|---|---|---|
| EasedUP ACv9 | Australian Curriculum v9 | Foundation – Year 10 |
| EasedUP Common Core | Common Core State Standards | K–12 Maths & ELA |
| EasedUP UK National Curriculum | UK National Curriculum | Key Stages 1–4 |

Claude selects the right server based on context — Australian school → ACv9, US school → Common Core, UK school → UK National Curriculum. If it can't tell, it will ask.
