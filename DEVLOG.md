# DEVLOG

> Home and source of truth for this project. It is the changelog, the decision record, and the context handoff for any new AI model or collaborator. **Read this whole file before doing anything.** Update it as work happens.

Project name: TBD
Last updated: 2026-11-19

---

## 1. Project Summary

An interactive, journalism-style website that tells a story about how bird migration reveals a bigger picture of our world. It is built for a friend who is working with the Audubon Society, who currently has an ArcGIS-based site.

The concept is a mesh of four things in one site:

- **Audubon's bird tracker**: tracking and species-level context
- **Cornell's bird migration visualizations** (BirdCast-style): continental-scale movement
- **Apple Weather's wind layer**: flowing, glowing particle trails over a map
- **Journalism / scrollytelling**: narrative-driven, reader-paced storytelling

Detailed scope and story goals: **TBD** (owner will add in Section 3).

## 2. Goals

1. Deliver a polished site the friend can actually use for the Audubon story.
2. **Learn.** The owner is building this from scratch to learn the tools, not just to ship.
3. Use industry-standard tools employers recognize, so the project doubles as a portfolio piece.

## 3. Story & Scope

_To be filled in by the owner._ Placeholders:

- Core narrative / thesis:
- Audience:
- Target species / regions / time span:
- Must-have features:
- Nice-to-have features:
- Deadline / launch context:

## 4. Collaboration Rules for AI (IMPORTANT)

The owner wants to figure things out themselves. Any AI model working on this project must follow these rules:

- **Do not volunteer code or files** for the owner to copy into the workspace. No unprompted snippets, scaffolds, configs, or boilerplate.
- Prefer explaining concepts, naming the right terms to search for, pointing to official docs, and describing approaches and trade-offs.
- Give hints and questions before answers. Escalate only if the owner asks.
- Reviewing code the owner wrote is welcome: explain bugs, suggest improvements, but let them make the fix.
- "Grunt work" (repetitive, mechanical, low-learning tasks) is fine to delegate **only when the owner explicitly asks**.
- The owner can override any of these rules for a specific request. Their latest instruction wins.
- Keep this file current. Log meaningful changes and decisions here (see Sections 7 and 8).

## 5. Tech Stack

Technologies the owner wants to work with (final choices per layer to be confirmed as they build):

| Area                             | Candidates     | Status    |
| -------------------------------- | -------------- | --------- |
| Frontend framework               | Next.js, React | Wanted    |
| Data handling at scale           | Python         | Wanted    |
| High-performance processing      | Rust           | Wanted    |
| GIS                              | ArcGIS         | Wanted    |
| Map rendering / particle effects | TBD            | Undecided |
| Hosting                          | TBD            | Undecided |
| Data sources                     | TBD            | Undecided |

Note: the friend's current site is on ArcGIS, so how this project relates to or integrates with it is an open question.

## 6. Architecture

TBD. Fill in as decisions are made: data flow from raw sources to the browser, how the map and animation layers are structured, how the narrative/scroll layer connects, and how it is deployed or embedded.

## 7. Decision Log

Record each significant decision with date, the options considered, what was chosen, and why.

| Date       | Decision                                    | Options considered | Reasoning                                                  |
| ---------- | ------------------------------------------- | ------------------ | ---------------------------------------------------------- |
| 2026-11-19 | Use DEVLOG.md as the single source of truth | n/a                | Keeps context for the owner and any future AI in one place |

## 8. Changelog

Newest first. One entry per meaningful change or work session.

### 2026-11-19

- Project kicked off. DEVLOG created.

## 9. Open Questions

- What is the full scope and story? (Section 3)
- How should this relate to the friend's existing ArcGIS site?
- Which bird data sources will be used, and at what scale?
- Which map and animation approach?
- Where will it be hosted, and does it need to embed into another site?

## 10. Resources & References

Add links to datasets, docs, tutorials, and inspiration here as they are found.

- Inspiration: Audubon bird tracker, Cornell BirdCast migration maps, Apple Weather wind layer, earth.nullschool.net
- Datasets mentioned as possibilities (unvetted): Movebank, Motus, eBird Status & Trends, GBIF
