---
name: ch-legal-mcp-skill
description: Official Switzerland (CH) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Switzerland Legal Research & Multi-Tier Case Law Skill (`ch-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Switzerland (CH)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `BGE 149 III 12 or SR 220 (OR/CO)`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Bezirksgerichte / Tribunaux de district / Preture & First-Instance Administrative Authorities across 26 Cantons
   - **Second Instance (Cantonal / Regional / Appellate):** 26 Cantonal Supreme & Appellate Courts (Obergerichte / Kantonsgerichte / Tribunaux cantonaux) & Federal Courts (BVGer, BStGer, BPatGer)
   - **Supreme & Constitutional Instance:** Schweizerisches Bundesgericht / Tribunal fédéral / Tribunale federale (BGer / TF — bger.ch)
   - **Primary Tiered Database:** Entscheidsuche.ch Unified Federal & 26-Canton Case Law Aggregator + BGer Eurospider (`https://entscheidsuche.ch`)
