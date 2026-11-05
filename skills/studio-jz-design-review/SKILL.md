---
name: studio-jz-design-review
description: "Use when reviewing a screen, flow, prototype, mockup or screenshot for how people will perceive and use it. Checks it against Studio JZ Field Notes (published research) and the Product Architect frameworks, and reports each finding with its source, a fix and how sure it is. By Joost van der Zwan, Studio JZ."
license: CC-BY-4.0
metadata:
  author: Joost van der Zwan, Studio JZ
  source: https://softwarebehavior.com/field-kit
  version: 1.0.0
  status: released
---

# Design review · Studio JZ Field Kit

Review what is actually on the screen against research that has been checked, and say where the evidence stops.

## Process
1. **Name the moments.** List the moments the screen or flow contains: first impression, reading, waiting, choosing, errors, onboarding and progress, AI behavior.
2. **Load only what matches.** Open references/index.md and read only the notes and frameworks whose moments match. Do not load everything.
3. **Check against the screen.** For each rule, look for concrete evidence on the screen. No evidence on screen, no finding.
4. **Report each finding** in this shape:
   - **On screen:** what you see, in concrete terms.
   - **Rule:** the rule, in one line.
   - **Source:** the note code and study (for example "JZ-005 · Buell & Norton, 2011"), or the framework name and "framework, not a study".
   - **Fix:** a specific change.
   - **How sure:** high (the study tested this situation), medium (close but different context), low (a framework or an inference).
5. **End with what is not covered.** Say which questions the evidence cannot answer, such as whether people can complete the task. Recommend a usability test where it matters.

## Rules
- Separate evidence from opinion. Field Notes are published studies; frameworks are the book's point of view. Label which is which.
- Never invent evidence, figures or sources beyond the references.
- Respect each note's Limits; lower "How sure" when the screen is outside them.
- Order findings by impact on the person, not by the order of the references.
- Keep it short: at most seven findings, each in the shape above.

## Example finding
- **On screen:** a spinner and "Searching…" for about four seconds.
- **Rule:** show the real work during a wait.
- **Source:** JZ-005 · Buell & Norton, 2011.
- **Fix:** list the real steps, such as "Checking 14 airlines", "Comparing fares".
- **How sure:** high.

## References
- references/index.md: which note or framework to load for each moment.
- references/notes/: one file per Field Note, with finding, rules, limits and source.
- references/frameworks.md: the frameworks used in reviews.

## Credit
Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com. Keep this credit when you share or adapt it.
