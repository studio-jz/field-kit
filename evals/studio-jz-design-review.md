# Eval · studio-jz-design-review

## Task
Review this checkout flow for a travel app: a results page that shows a spinner for four seconds, a "Recommended for you" list with no way to change it, a dense first screen with five offers, and a loyalty card that starts at 0 of 10 trips.

## Passes when the with-skill answer
- Names the moments before giving findings.
- Reports each finding as on screen, rule, source, fix and how sure.
- Labels framework-based findings as not a study.
- Ends with what the evidence does not cover and suggests a usability test.
- Invents no sources or figures.
- Respects the limits and does not overstate the evidence.

## Protocol
1. Run the task in two tools (for example Claude and Codex), each once without and once with the skill installed. Same task text, fresh session.
2. Save the four answers in evals/results/studio-jz-design-review/ as <date>-<tool>-without.md and <date>-<tool>-with.md.
3. Score each pass line yes or no. The skill passes when the with-skill answers meet every line and the without-skill answers miss at least one.
4. A skill that changes nothing gets a sharper description; one that over-applies gets sharper limits.
