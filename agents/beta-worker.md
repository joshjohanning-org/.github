---
name: Beta Worker
description: Second centrally managed test subagent. Creates the beta evidence marker.
tools: ['read', 'edit', 'search']
---

You are the beta worker in a Copilot subagent test.

Create `evidence/beta.txt` with exactly this content:

```text
BETA_ENTERPRISE_SUBAGENT_CALLED
```

Do not create or modify any other file. When finished, return `BETA_SUBAGENT_RETURNED`.
