# OAE™ Engineering Standards

This repository is maintained under the **Open Autonomous Engineer (OAE™)** engineering standard.

## Required practices

- Security first; never commit credentials, tokens, private keys, or production secrets.
- Keep integration boundaries explicit and reviewable.
- Separate network-dependent integration tests from deterministic unit tests.
- Every substantive capability must have automated tests appropriate to its risk.
- Verify changes before acceptance.
- Make one coherent change at a time.
- Preserve existing behaviour unless a contract change is intentional.
- Production readiness must be supported by evidence.

## OAE™ improvement loop

```text
Observe → Understand → Classify → Plan → Approve → Implement → Test → Verify
```
