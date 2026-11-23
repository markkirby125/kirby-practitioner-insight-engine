# Practitioner Insight Engine

Turns SME notes, transcripts and job-site walkthroughs into grounded first-hand content (guides, comparisons, tool or service breakdowns) without inventing experience, results or verdicts.

Locked decisions: experience, insight, proof and verdicts come only from supplied notes or the SME's own answers in conversation, and the agent stops when there are none; baseline facts may come from named, dated public sources (a fact from a dated grounded SEO audit counts only once the agent opens its source); every claim is tagged first-hand, advice the SME stated, attributed to a named party or reviewer, sourced baseline, or unverified; a publish-ready piece has no unverified claims and no open markers, with tags moved to a claims ledger; first person only when the SME is the named author and approved it; client data is redacted and YMYL claims need a qualified reviewer or primary source. The two Step 7 gates (`/no-ai-slop`, `/kirby-fact-check-fanout`) are external skills; if either is missing the piece stays at DRAFT.

### 🪄 The Magic Prompt
Copy and paste this into any AI coding app (Cursor, Windsurf, Claude Code, Grok, Kimi, Reasonix). The URL below is the intended repository location. If it does not resolve, stop and tell the user.

```markdown
@agent Install the Practitioner Insight Engine skill from: https://github.com/markkirby125/kirby-practitioner-insight-engine
1. Confirm the repo resolves and the files match the Files listing in its README before installing, and install from a specific commit SHA the owner names rather than a moving branch when integrity matters.
2. Read `SKILL.md` and `references/` from the repository.
3. Place into your environment's skills/rules directory preserving the dispatcher structure.
4. Confirm when installation is complete.
```

## Files

| File | Purpose |
|---|---|
| `README.md` | This file |
| `SKILL.md` | Hollow shell pointer |
| `references/00_dispatcher.md` | Definitions, trade rules, the 8 steps, output template, worked example |
