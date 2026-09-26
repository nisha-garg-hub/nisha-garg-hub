# Decision note

A lightweight template for turning an ambiguous operating question into a decision someone can act on.

## Question
What decision needs to be made?

## Context
What changed, what is stuck, and why does this decision matter now?

## Constraints
- What is fixed?
- What is flexible?
- What evidence is available?
- What remains unknown?

## Options
For each viable option, capture the tradeoff rather than only the upside.

| Option | Upside | Tradeoff | Evidence needed |
| --- | --- | --- | --- |
| A |  |  |  |
| B |  |  |  |

## Decision rule
State the rule that will determine the choice before selecting an option.

## Decision
Record the choice, owner, and what would cause the decision to be revisited.

## Validation
After implementation, check whether the result solved the original operating problem—not just whether the task was completed.

## Fictional worked example

**Question:** Should a small GTM team keep routing inbound leads manually or introduce a simple automated routing rule?

**Context:** Manual assignment is creating delays and inconsistent ownership as lead volume grows.

**Constraints:** Headcount is fixed, the CRM is already in place, and the team wants a change that can be reversed easily.

| Option | Upside | Tradeoff | Evidence needed |
| --- | --- | --- | --- |
| Keep manual routing | No implementation work | Delays and inconsistent handoffs continue | Current assignment time and error rate |
| Add a simple routing rule | Faster, more consistent ownership | Requires rule design and monitoring | Lead fields are reliable enough to route on |

**Decision rule:** Automate only if the required lead fields are consistently populated and the rule can be monitored without adding meaningful admin work.

**Decision:** Pilot a simple rule for one lead segment, with an owner responsible for reviewing exceptions.

**Validation:** Compare assignment speed, exception volume, and missed handoffs against the manual baseline before expanding the rule.
