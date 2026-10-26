# Handoff log — main

Append-only. Newest entry at the bottom. Written by `/handoff`.

---

## 2026-10-22 — Claude setup scaffolded

**Done**
- Added CLAUDE.md, .claude/ (settings, hooks, rules, agents, skills, commands),
  docs/STATE.md, docs/spec/, docs/decisions/0001–0003, docs/handoffs/.

**Decisions**
- 0001 MVP scope, 0002 visual encoding, 0003 page flow (all from the spec docs).

**Open questions / blockers**
- Stack, alignment method, visual direction A vs B, audience, MP4 pipeline.

**Next steps**
1. Pick the stack and write 0004-stack.md; fill the commands block in CLAUDE.md.
2. Adjust `paths:` globs in `.claude/rules/*.md` to the real source layout.
3. Build the no-audio path end to end: Import → Customize → Preview.

**Verified by**
- n/a (no code yet)
