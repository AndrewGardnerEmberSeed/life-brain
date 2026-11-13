---
type: topic
domain: operations
status: active
updated: 2026-11-13
sources: ["conversation 2026-11-13 — Andrew asked for a Second Brain in GitHub to replace the Life Plan doc", CLAUDE.md]
---

# How this brain works

A plain-English guide to the repository, for Andrew and for any agent reading it cold.

- **What it replaces.** The Google Doc *2026 Life Plan for Andrew Gardner 20260226* (241,000 characters, last edited
  9 March 2026). That document had grown too long for a session to read whole, so agents read fragments of it, which
  defeated its first rule: think globally before acting locally [LP §Instruction to the AI]. The wiki splits it into
  short pages and an index, so an agent reads the map and then exactly what it needs.
- **Nothing was thrown away.** The Doc's complete text is in `raw/2026-03-09-life-plan-google-doc.md`, never edited.
  Every wiki page cites the section it came from (`[LP §Section]`).
- **What was corrected.** Facts that moved after March (employment, ventures, companies, rent, age) are marked
  *superseded* on the page, with what replaced them and the source. Nothing was silently overwritten.
- **What isn't known.** Where no source in reach confirmed a fact, the page says **Unconfirmed (Qnn)** and the
  question is on [[open-questions]] and in the Andrew Actions Inbox on monday.
- **Locked pages** are Andrew's decisions: the priority rule ([[priority-arbitration]]), the personal statement on
  Elliott ([[statement-on-elliott]]) and the Choices document's text ([[choices-document]]). Agents don't change them.
- **Its sister brains.** SparkBoot and EmberSeed keep their own memories (`sparkboot-brain`, `emberseed-brain`). This
  brain links to them and doesn't copy them.
- **Privacy.** This repository holds health, family, money and psychological material. It stays private, and nothing
  in it goes into the business brains or anywhere a client can read without Andrew's say-so [CLAUDE.md].
- **How it stays current.** The monthly review ([[monthly-reviews]]) is the heartbeat: one page a month, written with
  Andrew, which updates [[2026-scorecard]] and [[where-we-are]].
