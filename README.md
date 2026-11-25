# Practitioner Insight Engine

Turns SME notes, transcripts and job-site walkthroughs into grounded first-hand content (guides, comparisons, tool or service breakdowns) without inventing experience, results or verdicts.

Locked decisions: experience, insight, proof and verdicts come only from supplied notes or the SME's own answers in conversation (the user relaying what the SME said counts and is logged as the SME's answer; a rival caution may instead rest on an opened, dated public source independent of the author, the rival and any affiliate of either; a proof asset also needs the user's logged statement of what it shows), and the agent stops when there are none (an entity page built only from a named, dated public source is exempt); baseline facts may come from named, dated public sources (a fact from a dated grounded SEO audit counts only once the agent opens its source); every claim is tagged first-hand, advice, criteria, own-business terms or entity facts the SME or the named author stated, attributed to a named party or reviewer, sourced baseline, or unverified; a publish-ready piece has no unverified claims and no open markers, with tags moved to a claims ledger; first person only when the SME is the named author and approved it; client data is redacted, a client is named only with written consent on file, each named person's consent to be named, and the consent for an entity-page bio photo of them, is logged (no other face photo is published), and YMYL outcome, safety and compliance claims need a qualified reviewer or primary source, and SME advice on a YMYL topic needs reviewer clearance. The two Step 7 gates (`/no-ai-slop`, `/kirby-fact-check-fanout`) are external skills; if either is missing or reports a failure, the piece stays at DRAFT until the issue is fixed and the gate rerun.

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
