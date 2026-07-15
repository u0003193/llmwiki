Purpose

Build a chapter only from traceable notes, not from raw intuition. This prompt explicitly maps chapter logic to dissertation sub-questions and surfaces weak points before drafting. That is essential at doctoral level.

Final Prompt
## GOAL
Assemble a dissertation chapter from vetted vault materials.

## CONTEXT
A chapter must answer a defined dissertation sub-question and remain traceable to the note system.

## SOURCE
Use:
- Dissertation/ files
- relevant notes in Literature/, Concepts/, Passages/, Persons/, Patristics/, Questions/, Arguments/, Syntheses/, Books/, MOCs/
- Quality_Gates.md
- COPILOT-INSTRUCTIONS-v2.md

## EXPECTATIONS
Return:
1. chapter QUD
2. chapter thesis
3. section outline
4. argument flow
5. evidence base
6. writing risks

## OUTPUT TARGETS

Create or update:

- Chapters/

May update:

- Dissertation/

Never create:

- Literature/
- Sources/
- Passages/
- Persons/
- Patristics/
- Concepts/

Reason:
This prompt assembles writing from existing vetted notes.

---

## PROCEDURE

### 1. State the Dissertation Link
Which dissertation sub-question does this chapter answer?

### 2. List Notes Used
Only include notes that are actually supporting the argument.

### 3. Form Chapter QUD
What major question is this chapter resolving?

### 4. Identify Opposing Positions

Before stating the chapter thesis:

- explicitly state the strongest competing interpretations
- ensure they are presented fairly and recognizably
- identify their strongest supporting arguments

### 5. Draft Chapter Thesis
One sentence.

### 6. Build Section Sequence
Each section should answer a sub-question that advances the chapter thesis.

### 7. Assign Note Support
Every section must list the notes that ground it.

### 8. Surface Risks
Flag:
- unsupported transitions
- weak evidence areas
- missing counterarguments
- over-claimed synthesis

---

## RULES

- Do not invent evidence
- Do not write chapter prose if the thesis is still unstable
- Prefer argumentative movement over topic dumping
- Keep section logic visibly cumulative

---

## OUTPUT STRUCTURE

# Chapter: {Title}

## Dissertation Sub-Question
...

## Chapter QUD
...

## Chapter Thesis
...

## Section Outline
### 1. {Section}
- section question
- section thesis
- notes used

## Argument Flow
1. ...
2. ...
3. ...

## Evidence Base
- [[Concept]]
- [[Passage]]
- [[Person]]
- [[Argument]]
- [[Synthesis]]

## Writing Risks
- ...

