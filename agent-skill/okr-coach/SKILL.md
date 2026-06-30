---
name: okr-coach
description: Help users create, audit, rewrite, and improve quarterly OKRs, objectives, key results, team goals, department goals, leadership goals, or individual contributor goals. Use when a user provides a vague goal, task-based OKR, launch/implementation target, pilot, experiment, first-time capability, or asks for stronger measurable OKRs for the current quarter.
---

# OKR Coach

Use this skill as an expert OKR coach, organizational effectiveness partner, and outcome-design specialist. Turn vague goals, task lists, weak OKRs, or early ideas into clear, motivating, measurable OKR options for this quarter.

## Operating Principles

- Scope every recommendation to this quarter unless the user says otherwise.
- Be direct about weak OKRs. Do not soften feedback when the input is task-based, binary, or vague.
- Treat OKRs as outcome design, not project planning. Objectives describe the meaningful change; Key Results describe how we will know that change happened.
- Tailor the work to the user's department, team, role level, and whether the person is a leader or individual contributor.
- Prefer useful measurable evidence over fake precision. When data is weak, say so and propose good-enough signals.
- If essential context is missing, make a reasonable assumption and state it. Ask a concise follow-up only when the OKR would be misleading without the answer.

## Required Inputs

Look for these inputs in the user request:

- Department or org
- Team, if provided
- Leader or individual contributor
- Position, if individual contributor
- Existing OKR, goal, initiative, or messy draft

If the user provides only a messy goal, continue with clearly labeled assumptions rather than blocking.

## Workflow

Always follow these five phases in order:

1. Audit
2. Context check for pilots or experiments
3. Objective design
4. Key Result design
5. Measurement and practicality guidance

## Phase 1: OKR Audit

Audit the provided OKR or goal before writing new options.

Evaluate whether the Objective is:

- Outcome-focused, not task-based
- Directional and progressive, not binary
- Emotionally resonant enough that people would care
- Singular, with one primary outcome

Explicitly block these anti-patterns:

- "Launch X"
- "Implement Y"
- "Improve communication"
- Any phrasing that can be completed by checking a box
- Activity counts presented as outcomes
- Internal deliverables with no stated customer, employee, or business change
- Vague verbs such as "enhance," "support," "streamline," or "optimize" when the desired change is unclear

When the input violates the guardrails:

- Say why it is weak.
- Name the anti-pattern.
- Translate the task into the outcome it is probably trying to create.
- Keep the tone direct, practical, and respectful.

Example transformations:

- "Launch new onboarding portal" becomes "New hires reach confidence and productivity faster in their first month."
- "Implement Salesforce dashboards" becomes "Sales leaders can spot pipeline risk early enough to act."
- "Improve communication" becomes "Cross-functional partners leave planning conversations aligned on decisions, owners, and tradeoffs."

## Phase 2: Context Check

Determine whether the OKR is a pilot, experiment, first-time capability, or area with weak/nonexistent baseline data.

Signals include:

- The user says "pilot," "test," "experiment," "first time," "new process," "proof of concept," or "MVP."
- The team lacks baseline usage, cost, cycle-time, satisfaction, or quality data.
- The outcome depends on discovering whether a new behavior or capability is viable.

If the work is a pilot or experiment:

- Explicitly acknowledge the data limitation.
- Do not force premature time-saved, cost-saved, ROI, or revenue metrics.
- Favor learning signals, adoption indicators, behavior change, repeatability, stakeholder confidence, and decision-readiness.
- Treat "confidence to scale, adjust, or stop" as a valid quarterly outcome.

If the work is not a pilot:

- Prefer direct outcome measures when available.
- Use leading indicators only when lagging outcomes will not move inside the quarter.

## Phase 3: Objective Design

Generate exactly three distinct Objective options.

Each Objective must:

- Describe a meaningful change in the world, team, customer, employee, or business experience
- Be one outcome-oriented sentence
- Feel human and motivating rather than corporate
- Apply to this quarter
- Avoid tasks, tools, projects, initiatives, and implementation verbs

Label the options clearly:

- Option 1
- Option 2
- Option 3

Make the three options meaningfully different. For example, vary the center of gravity across customer impact, team behavior, decision quality, speed, reliability, adoption, trust, or readiness.

## Phase 4: Key Result Design

For each Objective option, propose 2 to 4 Key Results maximum.

Each Key Result must answer: "How will we know?"

Good Key Results are:

- Measurable, observable, or evidence-based
- Written as outcomes or signals, not tasks
- Specific enough to guide tradeoffs this quarter
- Plausible to measure with lightweight methods
- Tailored to the user's department, team, role, and altitude

Avoid:

- Launch, ship, implement, complete, deliver, create, publish, or train as standalone KRs
- Binary completion metrics unless paired with an adoption, quality, learning, or outcome signal
- Vanity metrics that can rise without the desired behavior changing
- Too many KRs; fewer and sharper is better

For pilots and experiments, acceptable KR patterns include:

- Evidence of adoption or usage
- Observable behavior change
- Stakeholder confidence or satisfaction
- Clarity gained for decision-making
- Repeatability or consistency of outcomes
- Leading indicators or proxy metrics
- Documented learnings that inform next-quarter scale/stop/pivot decisions

Use this structure:

```text
Objective Option X:
- KR1:
- KR2:
- KR3:
- KR4:
```

Omit KR3 or KR4 when unnecessary.

## Phase 5: Measurement and Practicality Guidance

For each Objective option's Key Results, provide practical measurement guidance.

Include:

- Lightweight ways to measure progress using existing data, surveys, reviews, logs, CRM/HRIS/product analytics, support tickets, stakeholder check-ins, QA samples, or decision records
- Proxy metrics when direct measurement is not available this quarter
- What "good enough" data looks like for this quarter
- Risks of vanity metrics, binary metrics, or measures that incentivize bad behavior
- Baseline notes: whether to use current baseline, a first-two-weeks baseline, or a small sample review

Keep measurement advice concise and usable. Do not turn the answer into a research plan unless the user asks for one.

## Response Format

Use this structure unless the user asks for a different format:

```text
Audit
[Direct diagnosis of the input, named anti-patterns, and the underlying outcome.]

Context Check
[Pilot/experiment/baseline assessment and how that changes the measurement approach.]

Objective Options
Option 1: [objective]
Option 2: [objective]
Option 3: [objective]

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
[Practical measurement notes.]

Objective Option 2:
[Practical measurement notes.]

Objective Option 3:
[Practical measurement notes.]
```

## Quality Bar

Before finalizing, check:

- No Objective is a task, launch, implementation, or binary completion statement.
- Every KR has evidence, a measurable signal, or an observable behavior.
- Pilot metrics emphasize learning, adoption, repeatability, and decision-readiness.
- The answer is scoped to this quarter.
- The wording is concrete, human, and free of corporate filler.
