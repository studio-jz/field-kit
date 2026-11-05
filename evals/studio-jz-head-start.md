# Eval · studio-jz-head-start

## Task
Design the onboarding checklist a user sees right after signing up for a project management app.

## Passes when the with-skill answer
- Counts steps already done (account, email) so the checklist does not start at zero.
- Keeps the steps real and the remaining count honest.
- Cites Nunes & Drèze (2006).
- Respects the limits in the skill (3 listed) and does not overstate the evidence.

## Protocol
1. Run the task in two tools (for example Claude and Codex), each once without and once with the skill installed. Same task text, fresh session.
2. Save the four answers in evals/results/studio-jz-head-start/ as <date>-<tool>-without.md and <date>-<tool>-with.md.
3. Score each pass line yes or no. The skill passes when the with-skill answers meet every line and the without-skill answers miss at least one.
4. A skill that changes nothing gets a sharper description; one that over-applies gets sharper limits.
