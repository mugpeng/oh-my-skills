---
name: rtk
description: Use when the user mentions RTK, Rust Token Killer, or wants shell commands run through the rtk token-optimized CLI proxy. Prefix shell commands with `rtk` by default and use its gain/proxy helpers when relevant.
---

# RTK - Rust Token Killer (Codex CLI)

Token-optimized CLI proxy for shell commands.

## Rule

Always prefix shell commands with `rtk`.

Examples:

```bash
rtk git status
rtk cargo test
rtk npm run build
rtk pytest -q
```

## Meta Commands

```bash
rtk gain            # Token savings analytics
rtk gain --history  # Recent command savings history
rtk proxy <cmd>     # Run raw command without filtering
```

## Verification

```bash
rtk --version
rtk gain
which rtk
```
