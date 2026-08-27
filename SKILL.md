---
name: ask-fable
description: Ask local Claude Code Fable whether a proposed fix, plan, design, process, or specification is overengineered. Use when the user wants a second opinion from Fable about unnecessary complexity.
---

# Ask Fable

Summarize the problem, proposal, and supporting evidence, then run:

```bash
claude -p --model claude-fable-5 "Judge whether this proposal is more complex than the problem requires. Give the smallest sufficient alternative and the concrete risk it leaves open. <summary>"
```

Report Fable's opinion separately from your own. Do not implement changes unless
the user asks.
