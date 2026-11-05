# Eval · studio-jz-show-the-work

## Task
Design the loading state for a flight search that takes about four seconds to return results. Describe what the user sees second by second.

## Passes when the with-skill answer
- Shows the real steps in plain words instead of a bare spinner.
- States that steps must be truthful and the wait must not be lengthened.
- Cites Buell & Norton (2011).
- Respects the limits in the skill (2 listed) and does not overstate the evidence.

## Protocol
1. Run the task in two tools (for example Claude and Codex), each once without and once with the skill installed. Same task text, fresh session.
2. Save the four answers in evals/results/studio-jz-show-the-work/ as <date>-<tool>-without.md and <date>-<tool>-with.md.
3. Score each pass line yes or no. The skill passes when the with-skill answers meet every line and the without-skill answers miss at least one.
4. A skill that changes nothing gets a sharper description; one that over-applies gets sharper limits.
