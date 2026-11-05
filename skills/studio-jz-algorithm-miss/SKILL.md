---
name: studio-jz-algorithm-miss
description: "Use when designing, building or reviewing recommendations, forecasts, rankings, AI suggestions and generated drafts, autocomplete, and how a product behaves after its model gets something wrong. Applies Dietvorst et al. (2015, 2018): people abandon an algorithm after seeing it err, and come back when they can adjust it. From Software Behavior Field Notes by Joost van der Zwan (Studio JZ)."
license: CC-BY-4.0
metadata:
  author: Joost van der Zwan, Studio JZ
  source: https://softwarebehavior.com/notes/jz-006
  version: 1.0.0
  status: released
---

# One mistake · Software Behavior Field Note JZ-006

## The finding
In forecasting tests with a bonus for accuracy, people who watched a statistical model make mistakes chose their own judgment instead, though the model was better: their own forecasts had 15–29% more error. A follow-up study found the way back: when people could adjust the model's forecast, even slightly, they were far more willing to use it. The same mistake cost a model more trust than it cost a person. A small say in the result was enough to bring people back.

## Apply it
- Let people adjust what the system gives them: edit a suggestion, nudge a forecast, re-rank results. Even a small degree of control helps.
- Design the moment the system is wrong before it happens: acknowledge it, make correction easy, keep the person in charge.
- Set honest expectations about accuracy up front.
- When you apply this, name the source in one line, such as Dietvorst et al. (2015, 2018), so the person can check it.

## Do not
- Make the output take-it-or-leave-it.
- Promise a model that never errs. One visible mistake costs more than a modest claim.

## Limits
- Lab forecasting tasks with a bonus at stake, not everyday products.
- The studies measured whether people chose the model, not how they used it over months.
- Treat this as one input next to the person's own context and data, not as a rule that overrides them.

## Example
Before: A sales forecast shown as one fixed number; after one bad month the team stops opening it.
After: The forecast with a small adjustment control (for example ±10%) and a note on how often it has been within range (illustrative).

## Source and credit
Dietvorst, B. J., Simmons, J. P. & Massey, C. (2015). Algorithm aversion: People erroneously avoid algorithms after seeing them err. Journal of Experimental Psychology: General, 144(1), 114–126. https://doi.org/10.1037/xge0000033
Dietvorst, B. J., Simmons, J. P. & Massey, C. (2018). Overcoming algorithm aversion: People will use imperfect algorithms if they can (even slightly) modify them. Management Science, 64(3), 1155–1170. https://doi.org/10.1287/mnsc.2016.2643
Full note: https://softwarebehavior.com/notes/jz-006
Evidence and where each figure is confirmed: references/evidence.md
Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com. Keep this credit when you share or adapt it.
