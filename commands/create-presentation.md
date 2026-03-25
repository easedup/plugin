---
description: Create a classroom teaching presentation with slides. Usage: /easedup:create-presentation [topic, subject, year level, number of slides]
---

Create a classroom presentation for: $ARGUMENTS

## Steps

1. **Identify context** — subject, year level, and approximate number of slides (default: 8–12 slides if not specified)
2. **Search curriculum** — use EasedUP MCP to find relevant content descriptions and key concepts to cover
3. **Structure the slides** — plan a clear sequence: hook → content → consolidation → summary
4. **Generate the resource** — write the complete presentation as TipTap-compatible HTML

## Required Sections

- **Presentation Title**
- **Subject Area**
- **Year Level**
- **Curriculum Content Descriptions** — from EasedUP MCP
- **Learning Intention** — displayed on an early slide; what students will learn
- **Slide Structure** — use `<h2>` for slide titles, `<p>` and `<ul>` for content

### Slide Types to Include

| Slide | Purpose |
|---|---|
| Title slide | Topic, subject, year level |
| Learning intention | What students will learn today |
| Hook / activation | Engaging question, image description, or scenario |
| Content slides (4–8) | Key concepts, one main idea per slide |
| Worked example | Demonstrated example with steps |
| Check for understanding | Question or activity for students |
| Summary | Key takeaways |
| Reflection / exit | What did you learn? What's still unclear? |

For each slide, include:
- **Key Points** — concise bullet points (3–5 per slide maximum)
- **Visual** — describe any image, diagram, chart, or visual to include
- **Delivery Notes** — teacher prompts, questions to ask, or timing guidance (in `<blockquote>` tags)

Output the complete presentation as HTML.
