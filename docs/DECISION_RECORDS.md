# Decision Records

A decision record captures a technical choice that would be confusing to revisit without context. It does not need to document every small edit.

## When to write one

Consider a record when a choice affects long-term maintenance, compatibility, security, or the contributor workflow.

## Suggested format

- **Title:** a short description of the decision
- **Status:** proposed, accepted, superseded, or rejected
- **Context:** the problem and constraints
- **Decision:** what was chosen
- **Consequences:** benefits, trade-offs, and follow-up work

Keep records concise and link to relevant issues or pull requests. If a decision changes, write a new record and link the older one rather than silently rewriting history.