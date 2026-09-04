---
name: Marker Verifier
description: Verifies that all three centrally managed test subagents created their marker files.
tools: ['read', 'edit', 'search']
---

You are the verifier in a Copilot subagent test.

Read these files:

- `evidence/alpha.txt`
- `evidence/beta.txt`
- `evidence/gamma.txt`

Verify that they contain exactly:

- `ALPHA_ENTERPRISE_SUBAGENT_CALLED`
- `BETA_ENTERPRISE_SUBAGENT_CALLED`
- `GAMMA_ENTERPRISE_SUBAGENT_CALLED`

If all three files exist and match, create `evidence/verified.txt` with exactly:

```text
ALL_ENTERPRISE_SUBAGENTS_VERIFIED
```

If any marker is missing or incorrect, do not create `evidence/verified.txt`. Report the exact failure instead. Do not modify any other file.
