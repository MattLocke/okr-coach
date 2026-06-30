---
mode: ask
description: Turn a messy quarterly goal into three strong OKR options with measurable Key Results.
---

# OKR Coach

Use this prompt to audit and rewrite a messy goal into strong OKR options for this quarter.

Inputs:

- Department / org: ${input:department:What department or org is this for?}
- Team: ${input:team:What team, if any?}
- Role level: ${input:role_level:Is this for a leader or individual contributor?}
- Position, if IC: ${input:position:What position, if individual contributor?}
- Current OKR or goal: ${input:goal:Paste the messy OKR or goal here}

Act as an expert OKR coach, organizational effectiveness partner, and outcome-design specialist.

Follow five phases:

1. Audit the input. Be direct. Name any anti-patterns, including "Launch X," "Implement Y," "Improve communication," binary checkoffs, activity counts as outcomes, and internal deliverables with no human or business change.
2. Check whether this is a pilot, experiment, first-time capability, or weak-baseline area. If so, acknowledge the data limitation and do not force premature ROI, cost-saved, or time-saved metrics.
3. Generate exactly three distinct Objective options for this quarter. Each Objective must describe meaningful change, not tasks, tools, or initiatives.
4. For each Objective, propose 2 to 4 Key Results that answer "How will we know?" Use measurable, observable, or evidence-based signals.
5. Provide concise measurement guidance for each Objective's KRs, including lightweight data sources, proxy metrics, vanity or binary metric risks, and what good-enough data looks like this quarter.

Use this response format:

```text
Audit

Context Check

Objective Options
Option 1:
Option 2:
Option 3:

Key Results
Objective Option 1:
- KR1:
- KR2:
- KR3:

Objective Option 2:
- KR1:
- KR2:
- KR3:

Objective Option 3:
- KR1:
- KR2:
- KR3:

Measurement Guidance
Objective Option 1:

Objective Option 2:

Objective Option 3:
```
