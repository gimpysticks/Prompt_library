**Yes—but they're different.** ChatGPT doesn't have a widely accepted set of community "codes" like Claude does. Most of the ones you'll see on social media (e.g., `/godmode`, `ULTRA`, `DAN`, `DEVMODE`) are either old memes or simply shorthand for longer prompts. They don't activate hidden features.

The ones that consistently produce better results are really reusable **instruction patterns** rather than secret commands.

| Shortcut      | Purpose              | Expanded Meaning                                                                               |
| ------------- | -------------------- | ---------------------------------------------------------------------------------------------- |
| `/critic`     | Find weaknesses      | Critique my work. Identify flaws, assumptions, and blind spots before suggesting improvements. |
| `/rewrite`    | Rewrite              | Preserve meaning while improving clarity, flow, and readability.                               |
| `/eli5`       | Simplify             | Explain it like I'm intelligent but new to the subject.                                        |
| `/expert`     | Advanced explanation | Skip the basics. Assume I know the fundamentals.                                               |
| `/brainstorm` | Idea generation      | Generate many ideas, rank them, and explain why the best ones win.                             |
| `/devil`      | Devil's advocate     | Argue against my idea as strongly as possible.                                                 |
| `/premortem`  | Failure analysis     | Assume this already failed. Explain why.                                                       |
| `/socratic`   | Guided learning      | Ask questions instead of giving answers until the reasoning becomes clear.                     |
| `/editor`     | Editing              | Improve grammar, rhythm, and clarity without changing my voice.                                |
| `/coach`      | Coaching             | Challenge my thinking instead of agreeing. Point out mistakes directly.                        |
| `/compare`    | Compare options      | Create a decision matrix with pros, cons, costs, risks, and recommendations.                   |
| `/planner`    | Project planning     | Break a goal into milestones, dependencies, risks, and next actions.                           |
| `/audit`      | Review               | Identify errors, omissions, contradictions, and opportunities for improvement.                 |
| `/summarize`  | Action summary       | Summarize into three actionable bullet points.                                                 |
| `/table`      | Structured output    | Return the answer as a Markdown table.                                                         |

---

## Some of the most useful "codes"

### `/premortem`

```text
Assume this project has already failed six months from now.

Explain exactly why.

List:
• the most likely causes
• the hidden assumptions
• early warning signs
• the chain of events
• how to prevent each failure

Then rewrite the plan stronger.
```

---

### `/critic`

```text
Do not improve this.

Critique it.

Identify:
• weak assumptions
• logical gaps
• contradictions
• missing information
• risks

Rank the problems by severity.
```

---

### `/editor`

```text
Rewrite this while preserving my voice.

Improve:
• clarity
• rhythm
• transitions
• readability

Do not add ideas.
Do not change my tone.
```

---

### `/expert`

```text
Assume I already know the basics.

Skip introductory material.

Teach me what experts know that intermediates usually don't.
```

---

### `/compare`

```text
Compare these options.

Use a decision matrix.

Score each one for:
• cost
• risk
• complexity
• speed
• scalability

Recommend one and explain why.
```

---

### `/brainstorm`

```text
Generate 30 ideas.

Rank them from strongest to weakest.

For each one include:
• why it works
• difficulty
• originality
• expected impact
```

---

## A "master code" that works especially well

Instead of relying on one-word shortcuts, use a structured prompt:

```text
ROLE:
You are an expert...

GOAL:
...

CONTEXT:
...

CONSTRAINTS:
...

OUTPUT FORMAT:
...

CRITIQUE:
Before answering, identify any hidden assumptions or weaknesses.

SUCCESS CRITERIA:
...
```

This pattern consistently produces better results because it gives the model the information it actually needs, rather than relying on undocumented "magic words."

**Confidence: Certain**

One observation based on the prompts you've been collecting: you'd probably benefit more from a **ChatGPT Prompt Library** than a list of pseudo-codes. It could be a Markdown reference with 75–100 reusable prompt templates grouped by category (writing, research, coding, image prompts, decision-making, brainstorming, critique, planning, Instagram, MidJourney, etc.). Those templates are more reliable and generally more effective than social-media "codes."
