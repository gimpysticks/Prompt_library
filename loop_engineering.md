# Loop Engineering (OCR)

## 1. Introduction

Andrew Ng co-founded Google Brain and has personally trained more than 5 million developers through his programs.

The term "loop engineering" describes three feedback loops running on different time scales.

---

## 2. Three Loops Overview

- Loop 1: Agentic Coding Loop (minutes)
- Loop 2: Developer Feedback Loop (hours)
- Loop 3: External Feedback Loop (days/weeks)

The system applies whether you're building software, content, coaching, or services.

---

# Loop 1 — Agentic Coding Loop

The AI writes code, runs tests, debugs failures, and iterates autonomously.

## Prompt for Loop 1

You are a senior full-stack developer operating in agentic mode. Write the code, create tests, run them, debug failures, and iterate until all tests pass. Do not ask for approval between steps.

Task:
[Describe the feature, bug, or module.]

---

# Loop 2 — Developer Feedback Loop

Review the product direction rather than the implementation.

Questions:
- Does this solve the right problem?
- Are important features missing?
- Is the UX intuitive?
- Rewrite the product specification accordingly.

## Prompt for Loop 2

You are a product architect and technical lead. Evaluate the AI-generated output at the product level, then rewrite the specification to reflect your recommendations.

---

# Loop 3 — External Feedback Loop

Gather feedback from real users before continued development.

## Prompt for Loop 3

You are a growth strategist and product validation expert.

Design a 14-day alpha testing plan including:
- recruiting testers
- interview questions
- A/B tests
- meaningful metrics
- how to decide whether to iterate, pivot, or ship

---

## Closing

People pulling ahead are not better prompters—they are better loop designers. Spend your time on product judgment while the AI handles implementation.
