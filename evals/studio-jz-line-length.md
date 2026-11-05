# Eval · studio-jz-line-length

## Task
Set the body text for a long help-center article on a desktop layout that is 1440 px wide. Give the CSS for the article column and explain your choice.

## Passes when the with-skill answer
- Limits the line length in characters (about 55 to 75ch) instead of using the full width.
- Explains that speed, understanding and preference differ, and chooses for understanding here.
- Suggests testing with real content.
- Cites Dyson's line-length studies.
- Respects the limits in the skill (3 listed) and does not overstate the evidence.

## Protocol
1. Run the task in two tools (for example Claude and Codex), each once without and once with the skill installed. Same task text, fresh session.
2. Save the four answers in evals/results/studio-jz-line-length/ as <date>-<tool>-without.md and <date>-<tool>-with.md.
3. Score each pass line yes or no. The skill passes when the with-skill answers meet every line and the without-skill answers miss at least one.
4. A skill that changes nothing gets a sharper description; one that over-applies gets sharper limits.
