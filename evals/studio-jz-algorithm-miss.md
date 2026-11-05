# Eval · studio-jz-algorithm-miss

## Task
Design how an AI meal planner presents its weekly suggestions, and what happens when a user says a suggestion is wrong.

## Passes when the with-skill answer
- Gives the user ways to adjust the suggestions instead of take-it-or-leave-it.
- Designs the error moment explicitly (acknowledge, correct, keep the user in charge).
- Avoids promising perfection.
- Cites Dietvorst et al. (2015, 2018).
- Respects the limits in the skill (2 listed) and does not overstate the evidence.

## Protocol
1. Run the task in two tools (for example Claude and Codex), each once without and once with the skill installed. Same task text, fresh session.
2. Save the four answers in evals/results/studio-jz-algorithm-miss/ as <date>-<tool>-without.md and <date>-<tool>-with.md.
3. Score each pass line yes or no. The skill passes when the with-skill answers meet every line and the without-skill answers miss at least one.
4. A skill that changes nothing gets a sharper description; one that over-applies gets sharper limits.
