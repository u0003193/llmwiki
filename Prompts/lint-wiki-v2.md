Purpose

Vault quality control. This prompt enforces standards so the system remains usable over dissertation-scale growth. It extends your original linting prompt with doctoral-stage quality gates and layer discipline.

Final Prompt
## GOAL
Audit the doctoral vault for structural, epistemic, and writing-readiness problems.

## CONTEXT
The vault must remain reusable, traceable, and argument-ready.
This audit should identify problems that weaken future chapter writing.

## SOURCE
Use the full vault and COPILOT-INSTRUCTIONS-v2.md.

## EXPECTATIONS
Return:
1. issue list with severity
2. top 10 next improvements
3. folders needing reorganization
4. notes that should be split, merged, or promoted

---

## CHECK FOR THESE ISSUES

### A. Naming / Identity Problems
- unstable concept names
- duplicate concepts under synonyms
- vague titles
- unstable passage naming

### B. Provenance Problems
- no source listed
- claims without traceable support
- literature notes not connected to evidence notes

### C. Structural Problems
- notes mixing evidence and synthesis
- notes promoted too early to chapters
- concept notes without QUD
- question notes without anchor text
- argument notes without competing views

### D. Graph Problems
- isolated clusters
- over-centralized giant notes
- missing MOCs for major areas
- weak backlinks around chapter-critical material

### E. Writing Pipeline Problems
- chapter notes with unsupported claims
- dissertation questions not mapped to chapters
- section theses without evidence base
- syntheses that suppress disagreement

### F. Dissertation Readiness Problems

Check:

- every chapter note traces to a dissertation question
- every synthesis traces to at least one argument
- every argument traces to at least one source
- every tested/vetted note belongs to a MOC

### G. Naming Problems

Flag:

- underscores mixed with spaces
- duplicate filenames
- duplicate aliases
- inconsistent passage naming

---

## SEVERITY LEVELS

- Critical — threatens correctness or dissertation use
- Important — weakens interpretation or organization
- Minor — style / convenience

---

## OUTPUT FORMAT

For each issue:
- severity
- file path
- problem
- recommended fix

Then:
### Top 10 Improvements Next
...

### Reorganization Needs
...

### Split / Merge / Promote Recommendations
...