# Agent handoff — `llm-screening-prep`

Use this file at the **start of a new thread** so the agent has repo purpose, constraints, and pointers without re-reading Git history.

## What this repo is

A **learning / prep** space around **LLM-style technical screening** at large tech companies: how questions are framed, what knowledge they stress, and how to practice **without** reproducing confidential or stolen interview material.

It is **not** a dump of proprietary “leaked” questions. Any list that appears on social media should be treated as **unverified**; this repo should favor **clean-room** prompts you author yourself, plus public papers and docs.

## Why it exists (seed)

Public X thread (summary only; open for full context):

- **Kanika (@KanikaBK):** [post](https://x.com/KanikaBK/status/2047994100226687372?s=20) — describes very short screens, a large bank of LLM-style questions, and high comp for candidates who pass. Framed as “Big Tech” + “50 questions” + “leaked” narrative in the tweet text.

Curated capture of that seed (for your idea index):

- [jasonlarkin/slack_ideas — `curated/x-kanikabk-bigtech-llm-screening-2026-04.md`](https://github.com/jasonlarkin/slack_ideas/blob/main/curated/x-kanikabk-bigtech-llm-screening-2026-04.md)

## Hard constraints (do not violate)

1. **Do not** commit or redistribute content that is clearly **employer-confidential** or a verbatim **stolen** question bank.
2. **Do** separate “topic tags / skills checklist” from any specific company’s internal wording.
3. **Do** cite **public** sources (papers, blog posts, course notes) when teaching a concept.
4. If the user asks to paste a long leaked list into the repo, **refuse** the paste and offer: topic outline, original practice questions, or links to **legal** public materials.

## Suggested repo layout (evolve as you go)

```
llm-screening-prep/
  AGENTS.md           ← you are here
  README.md           ← user-facing overview + ethics
  docs/
    TOPIC_MAP.md      ← ML / systems / coding themes to cover
  practice/           ← optional: flashcards, CLI drills, notebooks
  LICENSE             ← pick MIT or Apache-2.0 for original code
```

## Concrete next tasks (pick any)

1. Add **`LICENSE`** (MIT is fine for tooling you write).
2. Add **`docs/TOPIC_MAP.md`**: sections (e.g. transformers, training, eval, inference, agents, security) with **3–5 bullet “skills to prove”** each — all original wording.
3. Add **`practice/`** stub: e.g. a `README.md` describing one daily drill format (no question text yet).
4. Optional: small script to **fetch oEmbed** for a *user-supplied* URL list (reuse pattern from [slack_ideas `scripts/x_reference.py`](https://github.com/jasonlarkin/slack_ideas/blob/main/scripts/x_reference.py)) — only for **public** posts the user owns or has rights to archive.

## Related repos

| Repo | Role |
|------|------|
| [slack_ideas](https://github.com/jasonlarkin/slack_ideas) | Link harvest, DM digest, `PROJECTS.md` triage; points here for this initiative. |

## Questions to ask the user if scope is unclear

- Target **audience**: self-study only, bootcamp, or interview prep business?
- **Depth**: ML theory vs systems vs Leetcode-style coding vs “LLM product sense”?
- **Output**: static site, CLI, Anki deck export, or prose only?

---

When this file drifts from reality, update **`README.md`** and this **`AGENTS.md`** in the same commit.
