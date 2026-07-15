Purpose

Strengthen graph quality without creating junk links. This prompt is meant to improve conceptual pathways, not merely increase link counts. That matches stronger knowledge-graph practice in academic Obsidian workflows and MOC-style navigation.

Final Prompt
## GOAL
Strengthen the note network by adding meaningful relationships, not decorative links.

## CONTEXT
The vault is a doctoral knowledge system.
Links must improve retrieval, argument visibility, and later chapter writing.

## SOURCE
Use:
- recently created or updated notes
- the broader vault
- COPILOT-INSTRUCTIONS-v2.md

## EXPECTATIONS
Return:
1. notes strengthened
2. orphan notes found
3. duplicate candidates
4. structural improvements recommended

---

## TASK

Review newly created or recently updated notes and improve their connectivity.

---

## PRIORITIES

### 1. Detect orphan notes
Find notes with insufficient relationships.
Add 2–5 meaningful links where justified.

### 2. Detect duplicate or near-duplicate notes
Examples:
- theosis vs deification
- mind vs nous
- participation vs communion

For each duplicate:
- recommend merge
- recommend alias
- or defend distinction

Do not merge automatically unless equivalence is strong.

### 3. Add typed relationships where possible
Prefer explicit relationships such as:
- broader than
- narrower than
- grounded in
- answers
- contested by
- developed by
- presupposes
- contrasted with

### 4. Strengthen navigation
Where useful add:
- Related Questions
- Related Passages
- Related Concepts
- See Also

### 5. MOC Connectivity

Every major research note should belong to at least one MOC.

Examples:

Patristics/
→ Basil MOC

Arguments/
→ Argument MOC

Syntheses/
→ Dissertation MOC

Chapters/
→ Dissertation MOC

---

## LINKING RULES

Add a link only if you can explain the relationship in one short phrase.

Bad:
- random related note dumping

Good:
- Grounded in [[Romans 5]]
- Develops [[Participation]]
- Answers [[How does deification relate to adoption?]]

## Bidirectional Link Rule

For every relationship:

A -> B

ensure

B -> A

unless relationship is explicitly one-way.

Examples:

Patristic Work
↔ Concept

Concept
↔ Argument

Passage
↔ Argument

Argument
↔ Synthesis

Synthesis
↔ Chapter

Chapter
↔ Dissertation Question

---

## OUTPUT FORMAT IN CHAT

### Notes Strengthened
- path — links added

### Orphans Found
- path — proposed connections

### Duplicate Candidates
- note A / note B — merge, alias, or distinction

### Recommended Structural Improvements
- recommendation