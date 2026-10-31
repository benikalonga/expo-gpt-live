# Upstream / Attribution

This repository is a copy of **[davidmokos/expo-gpt-live](https://github.com/davidmokos/expo-gpt-live)**, used for an AI code-review research project.

- Original repository: https://github.com/davidmokos/expo-gpt-live
- Copied from branch `main` at commit [`9e83073ef5b3`](https://github.com/davidmokos/expo-gpt-live/commit/9e83073ef5b3a986124d9141271c09443cbe8d5b) on 2026-10-31
- License: MIT. The original [LICENSE](./LICENSE) file is kept unchanged. All copyright belongs to the original authors.
- Full git history and original commit authorship are preserved.

Please send issues and contributions to the original project.

## Changes from the original

- Secrets, API keys, account IDs and personal data (emails, phone numbers, names) were replaced with placeholders such as `your_email@fakeemail.com`, `0810000000`, `YOUR_NAME` and `00000000-0000-0000-0000-000000000000`, across the whole git history.
- Personal email addresses in commit metadata were replaced with GitHub no-reply addresses or a placeholder. Author names are kept.
- AI agent configuration files (`.claude/`, `.agents/`, `.codex/`, `AGENTS.md`, `CLAUDE.md`, `.mcp.json`) were removed.
- Checked that all code comments, UI strings and documentation are in English, and that there are no screenshots or generated output folders; nothing needed changing.
- Automation was removed to keep this a plain source repository: CI/CD workflows (GitHub Actions, EAS workflows, Dependabot), helper/build/release scripts, editor and agent tool configs, and package.json scripts that pointed at removed files. Test suites are kept.
- The original LICENSE and its copyright notice are unchanged.
