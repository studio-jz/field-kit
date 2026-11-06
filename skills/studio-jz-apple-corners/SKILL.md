---
name: studio-jz-apple-corners
description: "Use when designing, building or reviewing buttons, cards, app icons, sheets, avatars and any rounded shape in an interface. Applies Bar and Neta (2006); Apple SwiftUI documentation: continuous corners ease into the bend; people prefer curves to sharp angles, but no study compares continuous with ordinary rounded corners. From Software Behavior Field Notes by Joost van der Zwan (Studio JZ)."
license: CC-BY-4.0
metadata:
  author: Joost van der Zwan, Studio JZ
  source: https://softwarebehavior.com/notes/jz-008
  version: 1.0.0
  status: in-review
---

# Apple corners · Software Behavior Field Note JZ-008

## The finding
A standard rounded corner is a straight edge plus a quarter circle, so the bend starts all at once at one point. A continuous corner (often called a squircle) eases into the bend: curvature builds up gradually and is tightest in the middle of the corner. Apple's SwiftUI offers both, as "quarter-circle" and "continuous curvature" corners. In a related study, people who saw objects for 84 ms liked curved versions more than sharp-angled ones (67% against 51%). The eye picks up the point where a straight edge suddenly becomes a curve; a gradual change in curvature has no such point. This mechanism is a design claim, not a tested finding.

## Apply it
- Use continuous corners where the platform offers them (SwiftUI RoundedRectangle with style .continuous; corner smoothing in Figma, the iOS preset).
- Keep nested corners concentric: inner radius equals outer radius minus the padding.
- Use the same corner style across a product, so cards, buttons and sheets match.
- When you apply this, name the source in one line, such as Bar and Neta (2006); Apple SwiftUI documentation, so the person can check it.

## Do not
- Claim that continuous corners are proven to be preferred; they have not been tested head to head.
- Fake continuous corners by turning up the radius; a bigger quarter circle still starts abruptly.

## Limits
- No study found that compares continuous corners with ordinary rounded corners directly.
- Bar and Neta compared curved objects with sharp-angled versions, not two kinds of rounded corner. 14 participants, grayscale images, 84 ms exposure.
- Strong associations (a snake, a chocolate bar) can override the curvature preference.
- Treat this as one input next to the person's own context and data, not as a rule that overrides them.

## Example
Before: Cards with 24 px quarter-circle corners and buttons with 8 px corners, each set by eye.
After: Continuous corners on cards and buttons, with nested elements using concentric radii.

## Source and credit
Bar, M. & Neta, M. (2006). Humans prefer curved visual objects. Psychological Science, 17(8), 645–648. https://doi.org/10.1111/j.1467-9280.2006.01759.x
Apple Developer Documentation. RoundedCornerStyle (SwiftUI): circular and continuous. developer.apple.com/documentation/swiftui/roundedcornerstyle
Full note: https://softwarebehavior.com/notes/jz-008
Evidence and where each figure is confirmed: references/evidence.md
Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com. Keep this credit when you share or adapt it.
