# aidlc-claude-trial

Scratch repo: checks whether AI-DLC's Claude harness hooks (`.claude/settings.json`) run in Devin cloud sessions.
Generated with `aidlc config --harness claude --yes` (AI-DLC 2.11.3). Logging hooks in `.claude/settings.json` and
`.devin/hooks.v1.json` append each hook's stdin to `$HOME/aidlc-hook-stdin.log`.
