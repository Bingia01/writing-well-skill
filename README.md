# /writing-well as a Claude Code Skill

(Built from *_On Writing Well_*, by William Zinsser)

Review and improve any writing using William Zinsser's *On Writing Well* principles.

Diagnoses clutter, weak verbs, broken unity, missing leads, and limp conclusions. Works on blog posts, docs, emails, reports, READMEs, and any nonfiction prose.

## What This Skill Does

Applies Zinsser's 10 core principles as a systematic review framework:

1. **Simplicity** — Strip every sentence to its cleanest components
2. **Active Verbs** — Your most important tool
3. **Be Yourself** — Authenticity over performance
4. **Unity** — Decide pronoun, tense, mood, scope, and one point before writing
5. **The Lead** — First sentence is everything
6. **The Ending** — Stop when you're done
7. **Words** — Respect your only tools
8. **Rewriting** — Where writing actually happens
9. **Enjoyment** — The reader can feel it
10. **Not a Contest** — Your only competition is yourself

Includes a 5-pass review process: **Clutter Audit → Verb Audit → Structure Audit → Lead/Ending Audit → Voice Audit**.

## Installation

Copy `SKILL.md` into your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/writing-well
cp SKILL.md ~/.claude/skills/writing-well/SKILL.md
```

Then invoke with `/writing-well` in any Claude Code session.

## Usage

```
/writing-well <file-path or paste text> [--focus clutter|structure|voice|lead|ending] [--mode review|rewrite|teach]
```

**Modes:**
- `review` (default) — Diagnose issues and show fixes
- `rewrite` — Produce the improved version with minimal commentary
- `teach` — Explain each principle before applying it

## Source

Principles extracted from William Zinsser's *On Writing Well* (30th Anniversary Edition). The book is the gold standard on nonfiction craft — this skill operationalizes it for daily use.
