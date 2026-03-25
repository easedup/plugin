---
description: Search and reference curriculum standards using EasedUP MCP tools — applies when creating resources that require curriculum content descriptions or achievement standards
---

## Available Curriculum MCP Servers

| Curriculum | Use When | MCP Tools |
|---|---|---|
| **Australian Curriculum v9** (ACv9) | Australian schools, Foundation–Year 10 | `mcp__claude_ai_EasedUP_ACv9__search`, `get`, `get_all` |
| **Common Core State Standards** | US K–12, Mathematics & ELA | `mcp__claude_ai_EasedUP_Common_Core__search`, `get`, `get_all` |
| **UK National Curriculum** | UK schools, Key Stages 1–4 | `mcp__easedup-uk-curriculum__search`, `get`, `get_all` |

## When to Search Curriculum

Always search curriculum standards when creating:
- Lesson plans
- Units of work
- Assessments
- Activities where curriculum alignment is important

If the teacher has already provided specific content descriptions, use those directly without searching.

## How to Determine Which Curriculum

1. Check if the teacher has specified (e.g., "ACv9", "Common Core", "Year 5 Maths")
2. Infer from context (Australian school → ACv9, US school → Common Core, UK school → UK National Curriculum)
3. If genuinely unclear, ask: *"Which curriculum framework are you using — Australian Curriculum v9, Common Core, or UK National Curriculum?"*

## MCP Tool Usage

### `search` — Natural language queries
Use for topic-based searches when you don't know the specific path.

Examples:
- "Year 5 fractions and decimals"
- "Grade 3 informational writing"
- "Key Stage 2 history"

### `get` — Retrieve by specific path
Use when you know the curriculum structure path.

Examples:
- `/mathematics/year-5`
- `/english/year-3`

The `get` tool accepts an optional `sections` array:
- `"level-description"` — Overview of what students learn at this level
- `"strands"` — Curriculum strands and content descriptions
- `"achievement-standards"` — Expected performance standards

### `get_all` — Browse available paths
Use to explore available curriculum paths when unsure of structure.

## Referencing Standards in Resources

When including curriculum content descriptions in a resource:
- Quote them accurately from the MCP tool results
- Include the content description code (e.g., `AC9MFN01`)
- Align learning intentions and success criteria directly to the standards
- Use achievement standards to calibrate expected performance levels
- Format content descriptions as a bulleted list under "Curriculum Content Descriptions"

## Example Workflow

1. Teacher asks for a Year 5 Maths lesson on fractions
2. Search: `mcp__claude_ai_EasedUP_ACv9__search("Year 5 fractions")`
3. Retrieve: `mcp__claude_ai_EasedUP_ACv9__get("/mathematics/year-5", sections: ["strands", "achievement-standards"])`
4. Extract relevant content descriptions and achievement standards
5. Build learning intentions and success criteria from these standards
6. Include codes and descriptions in the resource
