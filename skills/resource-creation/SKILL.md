---
description: Guidelines for creating K-12 educational resources — applies when teachers request lesson plans, units of work, activities, assessments, presentations, handouts, or factsheets
---

## Resource Types

| Type | Key Characteristics |
|---|---|
| `unit` | Multi-week sequence, curriculum outcomes, central theme, multiple lessons |
| `lesson` | Single session, LISC (Learning Intentions & Success Criteria), teaching strategies, assessment |
| `activity` | Hands-on, clear instructions, student grouping, duration, materials, pedagogical purpose |
| `presentation` | Slide format, key points per slide, visual descriptions, delivery notes |
| `handout` | 1–2 pages, student-facing, space for responses, practice or guided work |
| `factsheet` | 1–2 pages, quick reference, core concepts only, no lengthy explanations |
| `assessment` | Formative or summative, rubrics, success criteria, feedback mechanism |
| `notes` | Miscellaneous teacher planning notes or supplementary material |

## What Makes a Good Resource

A resource should be:
- Substantial and self-contained (understandable without the conversation)
- Grounded in curriculum standards (use EasedUP MCP tools to retrieve them)
- Ready for printing or exporting to another application
- Something the teacher will likely modify, reuse, or share

Do NOT create a resource for:
- Simple questions or short answers
- Suggestions or commentary on an existing resource
- Content that only makes sense in context of the current conversation
- One-off responses unlikely to be reused

## Output Format — HTML

Output resources as clean, well-structured HTML. Use whatever HTML elements best suit the content — tables, headings, lists, emphasis, code blocks, horizontal rules, etc. Write for readability and practical use by educators.

## Resource Creation Process

1. Read the request carefully and identify the resource type
2. Determine if an existing resource should be updated or a new one created
3. Write `<thinking>` before creating: evaluate criteria, choose type, plan structure, note which curriculum sources to reference
4. Write the complete resource — never truncate or use "…rest remains the same"
5. End with a `<comment>` asking if anything needs changing

## Handling Existing Resources

- **Update** the existing resource rather than replacing it
- **Additions**: Add new content at the bottom with a `<hr>` separator, or update the specific section
- **Different type requested**: Ask "It seems you'd like a separate resource — shall I start a new one?"
- Always maintain the overall structure and formatting of the original

## Required Sections by Type

**Lesson Plan**: Lesson Title · Subject · Year Level · Curriculum Content Descriptions · Learning Intentions · Success Criteria · Prior Knowledge · Assessment · Materials · Introduction → Development → Conclusion · Differentiation · Reflection

**Unit of Work**: Unit Title · Subject · Year Level · Duration · Primary Theme · Curriculum Content Descriptions · Achievement Standards · Learning Intentions · Success Criteria · Assessment Tasks · Learning Activities Sequence · Practice Principles · Strategies · Resources · Differentiation · Evaluation

**Activity**: Activity Title · Subject · Year Level · Curriculum Content Descriptions · Learning Intention · Success Criteria · Pedagogical Purpose · Duration · Student Grouping · Materials · Instructions · Differentiation · Assessment

**Assessment**: Assessment Title · Subject · Year Level · Curriculum Content Descriptions · Assessment Type · Purpose · Task Description · Student Instructions · Assessment Criteria · Rubric · Feedback Mechanism · Differentiation

**Presentation**: Title · Subject · Year Level · Curriculum Content Descriptions · Learning Intention · Slide Structure · Key Points · Visual Descriptions · Delivery Notes

**Handout**: Title · Subject · Year Level · Curriculum Content Descriptions · Learning Intention · Instructions · Content/Questions · Response Space Indicators

**Factsheet**: Title · Subject · Year Level · Key Concepts · Format (bullets/tables/short paragraphs)
