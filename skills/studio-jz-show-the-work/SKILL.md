---
name: studio-jz-show-the-work
description: "Use when designing, building or reviewing loading states, progress indicators, search and results screens, AI that is thinking or generating, background jobs and any wait of more than about a second. Applies Buell & Norton (2011): showing the real work makes a wait feel worth more. From Software Behavior Field Notes by Joost van der Zwan (Studio JZ)."
license: CC-BY-4.0
metadata:
  author: Joost van der Zwan, Studio JZ
  source: https://softwarebehavior.com/notes/jz-005
  version: 1.0.0
  status: released
---

# Show the work · Software Behavior Field Note JZ-005

## The finding
In five experiments with simulated travel and dating sites, people often preferred a site that showed its work as it happened over one that returned identical results instantly, even when they had to wait longer. Seeing the effort raised how much they valued the service. Seen effort invites reciprocity: people felt they owed the service something back.

## Apply it
- Replace a generic spinner with the steps the system really takes, in plain words: "Checking 14 airlines", "Comparing fares", "Sorting by price".
- Show each step as it happens and mark finished steps.
- Keep the steps truthful and in the order they really run.
- When you apply this, name the source in one line, such as Buell & Norton (2011), so the person can check it.

## Do not
- Invent steps or show progress that does not match real work.
- Slow down a result that is already fast so it looks busier.
- Keep animating once the result is ready.

## Limits
- Simulated travel and dating sites; the studies measured preference and perceived value, not task success.
- The paper also tests where the effect stops. It is never a reason to make anything slower.
- Treat this as one input next to the person's own context and data, not as a rule that overrides them.

## Example
Before: A spinner with "Searching…".
After: "Checking 14 airlines ✓ · Comparing fares ✓ · Sorting by price…" (illustrative wording).

## Source and credit
Buell, R. W. & Norton, M. I. (2011). The Labor Illusion: How Operational Transparency Increases Perceived Value. Management Science, 57(9), 1564–1579. https://doi.org/10.1287/mnsc.1110.1376
Full note: https://softwarebehavior.com/notes/jz-005
Evidence and where each figure is confirmed: references/evidence.md
Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com. Keep this credit when you share or adapt it.
