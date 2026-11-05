# Frameworks used in reviews

From The Product Architect by Joost van der Zwan (https://softwarebehavior.com/frameworks). These are the book's frameworks, not studies: label findings that rest on them as "framework, not a study".

## The Product Beneath the Interface
Layered stack · Chapter 2. The book's defining lens. Names the system layers that shape what the visible UI can honestly express.
- State
- Memory
- Permissions
- Timing
- Confidence
- Autonomy
- Orchestration
- Recovery
- Visibility
Use in a review: Check whether the screen honestly shows the system state, timing, confidence and recovery behind it.

## Negotiated Software Loop
Loop · Chapter 3. Describes the new contract between user and machine in probabilistic systems: intent, interpretation, suggestion, review, delegation, report back, correction, adaptation.
- Intent
- Interpretation
- Suggestion
- Review
- Delegation
- Report back
- Correction
- Adaptation
Use in a review: For AI and probabilistic features, check how the system and the person take turns and who has the last word.

## Behavior Design Questions
List · Chapter 4. A working list of questions to ask when designing behavior rather than interaction.
- Notice
- Infer
- Act
- Ask
- Reveal
- Reverse
- Back off
Use in a review: Ask all seven questions of any feature that acts on its own.

## The Trust Stack
Layered stack · Chapter 7. Names the structural materials of trust in intelligent systems, from expressive at the top to foundational at the bottom.
- Legibility
- Reversibility
- Controllability
- Recoverability
- Consistency
- Restraint
Use in a review: Check each layer from the bottom up; trust fails at the lowest missing layer.

## Workflow Authorship Canvas
Canvas · Chapter 5. A canvas for redesigning a workflow rather than wrapping it in better UI.
- Trigger
- Context
- Decision points
- Handoffs
- Repetition
- Bottlenecks
- System assistance
- Human control
Use in a review: For a flow, map where decisions, handoffs and repetition sit before judging the screens.

## Layers of Product Value
Layered stack · Chapter 1. Shows how product value appears across surface, flow, logic, behavior, and strategy.
- Surface
- Flow
- Logic
- Behavior
- Strategy
Use in a review: Say at which layer each finding sits, so a surface fix is not mistaken for a behavior fix.

## Behavior Prototype Checklist
List · Chapter 11. Scopes a prototype as an instrument for a named risk, from a sketch or clickable flow to running behavior.
- Assumption
- Trigger
- System response
- Visibility
- User control
- Failure case
- Recovery path
Use in a review: When a finding needs testing, scope the prototype that would test it.

## Behavior Spec
List · Chapter 4. A structured template for separating exact rules, interpretive assistance, evidence, measured reliability, authority, consequences, recovery, correction, and backoff.
- Trigger
- Inputs
- Confidence
- System action
- User control
- Visibility
- Correction
- Backoff
- Autonomy level
- Intent preview
Use in a review: For AI behavior, check that the spec separates exact rules from interpretive help and covers recovery and backoff.

## Operational Taste Test
List · Chapter 8. Converts taste from aesthetic preference into a set of operational decisions: what to automate, where to keep friction, what should not exist at all.
- Does this deserve automation?
- Does this deserve friction?
- Does this need visibility?
- Does this need restraint?
- Does this simplify the user's work?
- Should this exist at all?
Use in a review: For each automated step, ask whether it deserves automation, friction, visibility or restraint.

Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com
