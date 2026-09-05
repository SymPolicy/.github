# Contributing to SymPolicy repositories

This file is the organization default community health document for SymPolicy.
Repository-local `CONTRIBUTING.md` files override this file when present; they must not weaken the constitution below.

## Constitution: AI assistance and commit signatures

**Status:** Long-term organization-wide rule for **all** `SymPolicy/*` repositories.

1. **AI cannot be responsible for code**, and therefore **AI must not sign code**.
2. Do not merge commits onto managed branches whose Git **author** or **committer** is an AI or bot identity (for example, Cursor Agent, Claude Code / Claude, Copilot, or similar coding agents).
3. When a human uses AI to generate or assist with changes, that human must sign and submit under their own identity. AI may produce drafts only; it must not appear as the signed author.
4. Pull requests that still contain AI- or bot-signed commits are **drafts**: re-author under a human signature before merge. Do not merge them onto the default branch as-is.
5. This rule does not depend on which AI tool was used. Merges that violate it are governance defects and must be rolled back or re-signed.

## Related documentation

- Styio developer manual (EN/ZH): `SymPolicy/styio-dev-doc` → `standards/contributor-contract.md`
- Org constitution pages (when published under styio-dev-doc): `standards/ai-authorship-constitution.md`
