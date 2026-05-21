# Implementation Self Review

A Codex skill for compact engineering self-review after an implementation pass.

Use it before final delivery, or when an implementation needs a focused check for responsibility boundaries, unnecessary abstractions, defensive branches, naming clarity, test intent, documentation iteration scope, and same-class issues.

## When To Use

- After a first implementation pass, before final delivery.
- When user feedback questions code organization, naming, defensive checks, or abstraction necessity.
- When one issue may imply similar problems elsewhere and a same-class scan is needed.

## When Not To Use

- Full pull request or code review.
- Security audits or threat modeling.
- Architecture design or requirements planning before implementation.
- Reviews without a concrete implementation change or proposal.

## Installation

Clone this repository into your Codex skills directory:

```bash
git clone https://github.com/xiluoduyu/implementation-self-review.git ~/.codex/skills/implementation-self-review
```

Then invoke it by name:

```text
Use $implementation-self-review to review the current implementation for boundary clarity, necessity, and overengineering.
```

## License

MIT
