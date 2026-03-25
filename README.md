# EasedUP Plugin

An education productivity plugin primarily designed for [Claude](https://claude.ai), Anthropic's AI assistant — works in Claude Code, Claude.ai, and any product that supports MCP. Helps teachers create curriculum-aligned lesson plans, units of work, assessments, activities, and student-facing resources. Works standalone with your input, supercharged when you connect EasedUP curriculum servers.

## Installation

```bash
claude plugins add easedup/plugin
```

## Commands

Explicit workflows you invoke with a slash command:

| Command | Description |
|---|---|
| `/easedup:create-lesson` | Create a curriculum-aligned lesson plan with learning intentions, success criteria, and teaching strategies |
| `/easedup:create-unit` | Build a multi-week unit of work with sequenced lessons, assessment tasks, and achievement standards |
| `/easedup:create-assessment` | Design a formative or summative assessment with rubric anchored to curriculum standards |
| `/easedup:create-activity` | Generate a standalone classroom activity with instructions, grouping, and pedagogical purpose |
| `/easedup:create-presentation` | Create a slide-by-slide presentation outline with delivery notes |
| `/easedup:create-handout` | Write a student-facing handout with space for responses |
| `/easedup:create-factsheet` | Produce a concise quick-reference factsheet for students |
| `/easedup:search-curriculum` | Search and browse content descriptions and achievement standards |

All commands work **standalone** (describe your topic and year level) and get **supercharged** with curriculum MCP connectors.

## Skills

Domain knowledge Claude uses automatically when relevant:

| Skill | Description |
|---|---|
| `resource-creation` | Resource types, required sections, output format, and creation process for K-12 educational materials |
| `curriculum-alignment` | How to search and reference standards from EasedUP MCP servers across three curriculum frameworks |
| `teaching-strategies` | 16 core teaching strategies, common learning activities, and learning modes for K-12 |

## Example Workflows

### Creating a Lesson Plan

```
/easedup:create-lesson Year 5 fractions and decimals
```

Claude searches the curriculum for relevant content descriptions and achievement standards, selects appropriate teaching strategies, and outputs a complete, print-ready lesson plan.

### Building a Unit of Work

```
/easedup:create-unit Grade 3 ecosystems — 4 weeks
```

Get a week-by-week sequence with learning intentions, assessment tasks, teaching strategies, and differentiation built in.

### Designing an Assessment

```
/easedup:create-assessment Year 8 algebra — summative
```

Claude pulls achievement standards for the year level and uses them to anchor the rubric's performance levels.

### Creating a Classroom Activity

```
/easedup:create-activity Key Stage 2 persuasive writing debate
```

Get a ready-to-run activity with student instructions, grouping, materials list, and success criteria.

### Searching Curriculum Standards

```
/easedup:search-curriculum Year 6 statistics and probability
/easedup:search-curriculum Grade 5 informational writing Common Core
/easedup:search-curriculum Key Stage 3 history
```

Browse content descriptions and achievement standards across Australian, US, and UK curricula.

## Standalone + Supercharged

Every command and skill works without any integrations:

| What You Can Do | Standalone | Supercharged With |
|---|---|---|
| Lesson plans | Describe topic and year level | EasedUP MCP (live curriculum standards) |
| Units of work | Describe topic and duration | EasedUP MCP (content descriptions + achievement standards) |
| Assessments | Describe the task | EasedUP MCP (rubric anchored to achievement standards) |
| Activities | Describe the learning goal | EasedUP MCP (standards-aligned intentions) |
| Presentations & handouts | Describe content and context | EasedUP MCP (curriculum-referenced) |
| Curriculum search | Ask in plain language | EasedUP MCP (structured search + browse by path) |

## MCP Integrations

> If you see unfamiliar tool names or need to check which curriculum servers are connected, see [CONNECTORS.md](CONNECTORS.md).

Connect EasedUP curriculum servers for live standard lookups:

| Curriculum | Coverage | What It Enables |
|---|---|---|
| **Australian Curriculum v9** | Foundation – Year 10 | Live content descriptions, codes, achievement standards |
| **Common Core State Standards** | K–12 Maths & ELA | Grade-level standards and performance expectations |
| **UK National Curriculum** | Key Stages 1–4 | Programme of study and attainment targets |

See [CONNECTORS.md](CONNECTORS.md) for setup instructions and configuration details.
