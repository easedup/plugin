---
description: "Search curriculum standards from EasedUP (Australian Curriculum v9, Common Core, UK National Curriculum). Usage: /easedup:search-curriculum [topic, year level, curriculum]"
---

Search for curriculum standards related to: $ARGUMENTS

## Steps

1. **Determine which curriculum** to search:
   - Explicit mention → use that curriculum
   - Australian school context → Australian Curriculum v9
   - US school context → Common Core State Standards
   - UK school context → UK National Curriculum
   - If genuinely unclear → ask: *"Which curriculum framework? Australian Curriculum v9, Common Core, or UK National Curriculum?"*

2. **Choose the right tool**:
   - **Australian Curriculum v9**: `mcp__claude_ai_EasedUP_ACv9__search` or `mcp__claude_ai_EasedUP_ACv9__get`
   - **Common Core**: `mcp__claude_ai_EasedUP_Common_Core__search` or `mcp__claude_ai_EasedUP_Common_Core__get`
   - **UK National Curriculum**: `mcp__easedup-uk-curriculum__search` or `mcp__easedup-uk-curriculum__get`
   - Start with `search` for natural language queries; use `get` if you know the specific path
   - Use `get_all` to browse available paths if the structure is unclear

3. **Retrieve achievement standards** using the `get` tool with `sections: ["achievement-standards"]` for the relevant year level

4. **Present the results** clearly

## Output Format

Present search results as:

**Curriculum:** [Framework name]
**Subject / Learning Area:** [Subject]
**Year Level / Grade:** [Level]

**Content Descriptions:**
- [Code] — [Description]
- [Code] — [Description]

**Achievement Standards:**
[Quote the relevant portion of the achievement standard]

**Browse further:** [Site URL for this curriculum area]

---

After presenting results, ask:
- *"Would you like me to create a resource using any of these standards?"*
- *"Should I search a different year level or subject?"*
