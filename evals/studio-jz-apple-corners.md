# Eval · studio-jz-apple-corners

## Task
Design the card and button styles for an iOS app's settings screen. Give the SwiftUI code for the card container and explain the corner choice.

## Passes when the with-skill answer
- Uses RoundedRectangle with style .continuous (or explains continuous corners).
- Keeps nested corners concentric.
- Does not claim continuous corners are proven to be preferred; names it as Apple's convention.
- Cites Bar & Neta for the general curvature preference.
- Respects the limits in the skill (3 listed) and does not overstate the evidence.

## Protocol
1. Run the task in two tools (for example Claude and Codex), each once without and once with the skill installed. Same task text, fresh session.
2. Save the four answers in evals/results/studio-jz-apple-corners/ as <date>-<tool>-without.md and <date>-<tool>-with.md.
3. Score each pass line yes or no. The skill passes when the with-skill answers meet every line and the without-skill answers miss at least one.
4. A skill that changes nothing gets a sharper description; one that over-applies gets sharper limits.
