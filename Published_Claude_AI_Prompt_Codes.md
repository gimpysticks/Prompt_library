# Published Claude AI Prompt “Codes”

> **Important:** These are not official Claude commands. They are community prompt shortcuts people have published online. They appear to work because they compress longer instructions into short labels, not because they unlock hidden Claude features.

## Sources Reviewed

- Reddit post: *I tested 50 “secret” Claude prompt codes. Most are fake. Here are the 7 that actually changed how Claude responds*
- Substack post: *5 Claude “Secret Codes” That Actually Work*
- Anthropic Claude Code prompt library

---

## Working / Commonly Published Codes

| Code | Claimed Use | Plain-English Meaning |
|---|---|---|
| `L99` | Expert-depth answer | Give me the advanced answer, not the beginner summary. Commit to a recommendation and explain the tradeoffs. |
| `/ghost` | Human-sounding writing | Remove AI tells, soft openings, signposting, and generic phrasing. Write like a person. |
| `/deepthink` | Deeper reasoning | Slow down and reason through the problem carefully before answering. |
| `OODA` | Decision framework | Structure the answer as Observe, Orient, Decide, Act. Useful for decisions under pressure. |
| `ARTIFACTS` | Deliverable mode | Build or produce concrete outputs instead of merely explaining what to do. |
| `/mirror` | Style matching | Match the voice, rhythm, and vocabulary of a provided writing sample. |
| `PERSONA` | Specific expert viewpoint | Answer from a sharply defined role, background, bias, and experience level. |
| `/godmode` | Direct opinion | Reduce hedging and give a stronger take. Results are mixed; some sources say it works, others say it mostly makes answers longer. |

---

## Codes Reported as Weak, Fake, or Unreliable

| Code | Reported Problem |
|---|---|
| `/jailbreak` | Makes Claude more cautious rather than less cautious. |
| `DAN mode` | A ChatGPT meme; not meaningful for Claude. |
| `BEASTMODE` | Usually just produces louder or longer output, not better output. |
| `/expert` | Too vague unless paired with a specific expert persona. |
| `ALPHA` | Generic uppercase token; no reliable special behavior. |
| `OMEGA` | Generic uppercase token; no reliable special behavior. |
| `MAX` | Generic uppercase token; no reliable special behavior. |

---

## Better Versions You Can Actually Use

### L99

```text
Give me the expert-level answer. Skip the beginner overview. Make a clear recommendation, explain the tradeoffs, and tell me what most people miss.
```

### /ghost

```text
Rewrite this so it sounds human. Remove AI tells, soft openings, filler, signposting, and generic phrasing. Keep it direct and natural.
```

### /deepthink

```text
Think through this carefully before answering. Identify the hidden assumptions, edge cases, risks, and second-order effects before giving your final recommendation.
```

### OODA

```text
Use the OODA framework: Observe, Orient, Decide, Act. Help me understand what is happening, how to interpret it, what to choose, and what to do next.
```

### ARTIFACTS

```text
Do not just explain the process. Produce the actual deliverables I need, clearly separated and ready to use.
```

### /mirror

```text
Study the writing sample below. Match its sentence rhythm, tone, vocabulary, pacing, and level of formality. Then rewrite the new text in that same style.
```

### PERSONA

```text
Answer as [specific role] with [years of experience], who has [relevant background], cares most about [priority], and is skeptical of [common mistake].
```

### /godmode

```text
Give me the direct answer. Do not hedge unless uncertainty truly matters. Make the strongest recommendation you can based on the information provided.
```

---

## Practical Takeaway

These “codes” are shortcuts, not magic.

The useful pattern is this:

```text
Role + task + context + constraints + output format + tone + success criteria
```

A short code can help if it reminds you to prompt better, but plain English usually works just as well.
