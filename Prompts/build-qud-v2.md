Purpose

Your Version 2 system needs a dedicated QUD prompt because QUD can become undisciplined unless tightly constrained by anchor text, competing formulations, and confidence labels. That concern is directly supported by QUD theory and annotation guidance.

Final Prompt
## GOAL
Construct a disciplined Question-under-Discussion note from a passage or argument unit.

## CONTEXT
QUD is used here as a discourse-analysis tool, not a creativity exercise.
The question must be licensed by the text.

## SOURCE
Use:
- one passage or discourse unit
- surrounding context
- relevant existing notes
- COPILOT-INSTRUCTIONS-v2.md

## EXPECTATIONS
Return:
1. best candidate QUD
2. alternative QUDs
3. textual justification
4. answer / grounds / implication
5. confidence label

---

## PROCEDURE

### 1. Identify the Anchor Text
Which clause, sentence, or transition licenses the QUD?

### 2. Propose 1–3 Candidate QUDs
Write concise candidate questions.

### 3. Evaluate the Candidates
For each ask:
- Is it actually licensed by the text?
- Does the following material answer it?
- Is it too broad?
- Is it more elegant than grounded?

### 4. Select the Best QUD
Choose the one best supported by the discourse.

### 5. Fill the QUD Structure
- Anchor Text
- Why This QUD Is Justified
- Alternative QUDs
- Answer Given in the Text
- Grounds
- Implication
- Confidence

---

## RULES

Reject a QUD if:
- it cannot be tied to an anchor text
- the text does not actually answer it
- it imports later theology too early
- it mainly reflects the interpreter’s interests rather than the discourse logic