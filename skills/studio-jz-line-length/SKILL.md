---
name: studio-jz-line-length
description: "Use when designing, building or reviewing articles, documentation, help pages, blog posts, long-form reading, email bodies, terms and any column of body text. Applies Dyson and colleagues (1998–2004): long lines are read faster, but about 55 characters per line is understood better. From Software Behavior Field Notes by Joost van der Zwan (Studio JZ)."
license: CC-BY-4.0
metadata:
  author: Joost van der Zwan, Studio JZ
  source: https://softwarebehavior.com/notes/jz-003
  version: 1.0.1
  status: in-review
---

# Line length · Software Behavior Field Note JZ-003

## The finding
Reading from screen, text set at 100 characters per line was read faster than text at 25. But people rated about 55 characters per line as easiest to read, and a later study found 55 was understood better than 100. Speed, understanding and preference point in different directions. Every new line is a jump back to the left edge, so long lines mean fewer jumps and less scrolling. Faster is not the same as clearer.

## Apply it
- Decide what the text is for. For skimming and scanning, a wider measure is fine; for study and understanding, aim for about 55 characters per line.
- Set the measure in characters (for example max-width in ch units), not in pixels, so it holds across type sizes.
- Test with your own content, typeface and devices.
- When you apply this, name the source in one line, such as Dyson and colleagues (1998–2004), so the person can check it.

## Do not
- Pick a line length by feel alone. What feels easiest is not what is read fastest or understood best.
- Present one line length as best for every purpose.

## Limits
- These studies used one typeface and size on desktop screens; mobile was not tested.
- Speed, understanding and preference were measured separately and can conflict.
- Status: the comprehension finding for 55 characters is being checked in the full paper; this skill ships when it is confirmed.
- Treat this as one input next to the person's own context and data, not as a rule that overrides them.

## Example
Before: A help article spread across a full-width 1400 px column, about 160 characters per line.
After: Body text capped at about 60ch for the article, with a wider layout kept for tables and code.

## Source and credit
Dyson, M. C. & Kipping, G. J. (1998). The effects of line length and method of movement on patterns of reading from screen. Visible Language, 32, 150–181.
Dyson, M. C. & Haselgrove, M. (2001). The influence of reading speed and line length on the effectiveness of reading from screen. International Journal of Human-Computer Studies, 54, 585–612.
Dyson, M. C. (2004). How physical text layout affects reading from screen. Behaviour & Information Technology, 23(6), 377–393.
Full note: https://softwarebehavior.com/notes/jz-003
Evidence and where each figure is confirmed: references/evidence.md
Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com. Keep this credit when you share or adapt it.
