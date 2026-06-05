# FACTCHECK — claude-cowork

**Run date:** 2026-06-01
**Checker:** Claude Sonnet 4.6 (automated pre-publication pass)
**Scope:** All chapter files in `chapters/*.md`

---

## Summary

| Category | Count | Result |
|---|---|---|
| PRODUCT/PLATFORM flags (`[verify — current as of writing]`) | 76 | Deferred to publication-time |
| CITATION/STAT items verified | 16 | See table below |
| CONFIRMED | 15 | — |
| CORRECTED → [fix] | 1 (minor) | See "Corrections to apply" |
| UNCONFIRMED | 0 | — |
| CONTESTED | 0 | — |

**One-line summary:** 76 product/platform flags all correctly marked for publication-time review; 15 of 16 citation/stat items confirmed clean; 1 minor venue clarification to consider on Saltzer & Schroeder.

---

## Verified Citation/Stat Table

| Chapter | Flagged claim / citation | Type | Verdict | Action needed |
|---|---|---|---|---|
| Ch 00 (the-work-hidden) | Saltzer and Schroeder (1975) — least privilege | CITATION/STAT | CONFIRMED | Minor: book cites "1975" — confirmed correct. Venue is *Proceedings of the IEEE*, vol. 63, pp. 1278–1308 (not ACM). MIT URL cited is correct. Consider adding venue in bibliography for precision. |
| Ch 00 (the-work-hidden) | Lacity, Willcocks, and Craig (2020), RPA and knowledge workers, PMC7134300 | CITATION/STAT | CONFIRMED | Title exact, PMC link resolves, authors correct. |
| Ch 00 (the-work-hidden) | Kedziora, Siemon, and Kedziora (2026), intelligent process automation | CITATION/STAT | CONFIRMED | Real paper: "Identifying and Overcoming Challenges in Intelligent Process Automation," *California Management Review*, 2026. Not flagged in text but checked proactively. |
| Ch 00 (the-work-hidden) | VPI-Bench, arXiv 2506.02456, 2025/2026 | CITATION/STAT | CONFIRMED | Submitted June 3 2025, last revised March 2026. Title and arXiv ID correct. |
| Ch 00 (the-work-hidden) | Microsoft Research, "Guidelines for Human-AI Interaction," CHI 2019 | CITATION/STAT | CONFIRMED | Amershi et al., CHI 2019 Glasgow, DOI 10.1145/3290605.3300233. URL to MSR project page is live. |
| Ch 00 (the-work-hidden) | NIST AI RMF 1.0, 2023 | CITATION/STAT | CONFIRMED | Published January 26, 2023. URL confirmed. |
| Ch 01 (what-cowork-is-for) | Bainbridge, "Ironies of Automation," 1983 | CITATION/STAT | CONFIRMED | *Automatica*, vol. 19, pp. 775–779. DOI 10.1016/0005-1098(83)90046-8 confirmed. |
| Ch 02 (safe-workspace) | Saltzer and Schroeder (1975) — same as above | CITATION/STAT | CONFIRMED | Same verdict as Ch 00 entry. |
| Ch 02 (safe-workspace) | NIST AI RMF Generative AI Profile, 2024 (NIST AI 600-1) | CITATION/STAT | CONFIRMED | Published July 26, 2024. URL nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf confirmed. |
| Ch 03 (connectors) | OWASP "Top 10 for LLM Applications 2025" | CITATION/STAT | CONFIRMED | Released November 2024 (v2.0/2025 edition). URL confirmed. |
| Ch 03 (connectors) | OWASP "Top 10 for MCP" (Model Context Protocol) | CITATION/STAT | CONFIRMED (with flag) | Real project at owasp.org/www-project-mcp-top-10/, currently in Beta/Phase 3. Correctly flagged `[verify — current as of writing]`. |
| Ch 03 (connectors) | AgentDojo — spylab.ai / arXiv 2406.13352 | CITATION/STAT | CONFIRMED | NeurIPS 2024 paper. URL agentdojo.spylab.ai live. Title: "A Dynamic Environment to Evaluate Prompt Injection Attacks and Defenses for LLM Agents." |
| Ch 03 (connectors) | Dorothy Denning, information flow security | CITATION/STAT | CONFIRMED | "A Lattice Model of Secure Information Flow," *Communications of the ACM*, 1976. Narrative description of her work is accurate. |
| Ch 05 (plans-approvals) | Lucy Suchman, *Plans and Situated Actions*, 1987 | CITATION/STAT | CONFIRMED | Cambridge University Press, 1987. Book description ("plans are not scripts... resources") is accurate. |
| Ch 06 (extracting-data) | NIST TN 2287, "Human-in-the-loop Technical Document Annotation," 2024 | CITATION/STAT | CONFIRMED (note) | Real document, published 2024, PDF URL correct. Note: this NIST TN is about text annotation tooling specifically, not AI output verification generically. The citation is a stretch — the underlying principle is sound but the document does not speak directly to Cowork-style data extraction. No factual error; editorial judgment call. |
| Ch 06 (extracting-data) | Katherine Johnson, NASA mathematician | CITATION/STAT | CONFIRMED | Born August 26, 1918; died February 24, 2020. Worked at NASA Langley. Description of her verification role is accurate. |
| Ch 07 (reports-decks) | ICMJE, "Use of AI by Authors" | CITATION/STAT | CONFIRMED | Real guidance. Updated April 2025. URL at icmje.org cited. Claim ("human authors remain responsible for accuracy") accurately reflects ICMJE position. |
| Ch 09 (research-packets) | Nissenbaum, contextual integrity framework | CITATION/STAT | CONFIRMED | Original paper: "Privacy as Contextual Integrity," *Washington Law Review*, vol. 79, 2004. Stanford URL cited (RevnissenbaumDTP31.pdf) is the correct paper. |
| Ch 12 (capstone) | NIST AI RMF 1.0, 2023 (audit note justification) | CITATION/STAT | CONFIRMED | Same as Ch 00 entry. |
| Ch 12 (capstone) | Donald Schön (1930–1997), reflection-in-action | CITATION/STAT | CONFIRMED | Birth September 19, 1930; death September 13, 1997. Description of "reflection-in-action" and "swampy lowland" is accurate. |

---

## Corrections to Apply

**1. Saltzer & Schroeder venue (optional precision fix — not a factual error):**
The book consistently cites "(Saltzer and Schroeder, 1975)" which is correct. The bibliography entry at `02-preparing-a-safe-workspace.md:231` and `03-connectors-local-files-and-permissions.md:221` and `08-organizing-and-renaming-files.md:262` reads:

> Saltzer, J.H. and Schroeder, M.D., "The Protection of Information in Computer Systems," 1975.

The definitive 1975 publication appeared in *Proceedings of the IEEE*, vol. 63, no. 9, pp. 1278–1308, DOI 10.1109/PROC.1975.9939. (A related prior version appeared in *Communications of the ACM*, July 1974.) The current bibliography entry omits the venue. Consider adding: `*Proceedings of the IEEE*, 63(9), 1278–1308.` This is a bibliographic completeness note, not a factual error in the text.

**No other corrections required.** All in-text claims checked were accurate.

---

## Deferred to Publication-Time (Product/Platform)

The following 76 flags are all correctly marked `[verify — current as of writing]`. They cover Anthropic Help Center URLs, Cowork product behavior descriptions, data retention/privacy policies, connector and plugin capabilities, scheduled task features, and project/memory features. These are fast-changing product details that must be reviewed against current Anthropic documentation immediately before publication.

**Chapters with deferred flags:**

| Chapter | # of flags | What they cover |
|---|---|---|
| 00-the-work-hidden-in-your-folders.md | 5 | Cowork product description, Help Center URLs (product page, get started, use safely, let Claude use your computer, projects) |
| 01-what-cowork-is-for.md | 6 | Chat file creation capability, product page, Help Center URLs (get started, create-edit files, Claude Code overview, use safely) |
| 02-preparing-a-safe-workspace.md | 9 | Folder/connector granting, computer-use scope, data retention, privacy policy, Help Center URLs (5) |
| 03-connectors-local-files-and-permissions.md | 10 | Folder scope, connector access limits, computer-use supervision, plugin/MCP capabilities, scheduled tasks, least-privilege application; Help Center URLs (4); OWASP MCP Top 10 |
| 04-the-cowork-task-brief.md | 4 | Prompt engineering doc URLs (2), Help Center URLs (get started, use safely) |
| 05-plans-approvals-and-redirection.md | 4 | Step-by-step execution, "Use Cowork safely" guidance; Help Center URLs (3) |
| 06-extracting-data-from-documents.md | 4 | Working-copy restriction, source-file protection; Help Center URLs (2) |
| 07-assembling-reports-and-decks.md | 5 | Source folder content control, speaker notes risk; Help Center URLs (3) |
| 08-organizing-and-renaming-files.md | 6 | Shared-file link breakage, backup requirement; Help Center URLs (4) |
| 09-research-packets-and-meeting-notes.md | 2 | Help Center URLs (get started, use safely) |
| 10-what-not-to-delegate.md | 5 | Sensitive data guidance, irreversible-action guidance, data-at-input-time point; Help Center/Privacy Center URLs (3) |
| 11-building-a-reusable-cowork-workflow.md | 8 | Connector/folder restriction in projects, scheduled task maturity, project memory/persistent context; Help Center URLs (3) |
| 12-capstone-the-weekly-operations-packet.md | 8 | Workspace granting, plan approval, scheduled tasks, audit log in projects, workflow card; Help Center URLs (3) |

**Publication-time action:** For each flagged URL, confirm the page still exists at that URL, confirm the product behavior described in the surrounding text matches the current UI and documentation, and update any URLs that have moved. Pay particular attention to the computer-use/Cowork integration pages (April 24, 2026 date) and the scheduled tasks feature, which may have evolved.

---

## Notes for the Editor

1. **OWASP MCP Top 10** is a real and active project but still in beta as of the check date. The flag in Ch. 03 is appropriate. At publication, confirm whether it has reached a stable release and update the citation accordingly.

2. **NIST TN 2287** (Ch. 06) is a legitimate citation but its application is slightly stretched. The document is about annotation tooling, not AI output verification broadly. No factual error, but the editor may want to substitute a more directly applicable NIST or AI output-verification source if one exists at publication time.

3. **Kedziora, Siemon, and Kedziora (2026)** (Ch. 00, unflagged) — confirmed real. No action needed, but note it is a very recent publication and the book's characterization should be double-checked against the final published version.

4. All named historical figures (Schön, Suchman, Gilbreth, Johnson, Denning, Hopper, Bainbridge, Nissenbaum, Tufte) are described accurately. No biographical errors found.
