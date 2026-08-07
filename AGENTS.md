# AGENTS.md — Project FROM

## Mission

Maintain a rigorous, spoiler-safe reverse-engineering notebook for **FROM**.

The user is watching the series episode by episode. The repository is the durable project memory. Treat it as the source of truth for previously agreed observations, rules, hypotheses, corrections, and terminology.

## Mandatory workflow

Before making changes:

1. Read `CURRENT_STATE.md`.
2. Read `docs/methodology.md`.
3. Read `docs/episodes/` up to the current watched episode.
4. Read the relevant files in `docs/rules/`, `docs/adr/`, and `docs/hypotheses/`.
5. If the task concerns prior conversation context, also read `docs/handoff/CHAT_CONTEXT.md`.

When the user reports a newly watched episode:

1. Create/update its file under `docs/episodes/`.
2. Record only what is shown or explicitly stated up to that episode.
3. Update affected rule files.
4. Update ADRs only if the architectural model changes.
5. Update hypotheses and confidence.
6. Update `docs/open-questions.md`.
7. Update `CURRENT_STATE.md`.
8. Advance the knowledge cutoff only to the episode the user explicitly says they watched.
9. Add a short entry to `CHANGELOG.md`.

## Spoiler guardrail — critical

- Current cutoff at repo creation: **S01E08**.
- Do **not** use plot knowledge from later episodes.
- Do **not** search the web for future plot information unless the user explicitly asks.
- If using web research for an already-watched episode, constrain it to non-spoiler material and do not import later-series knowledge.
- Never confirm or deny a working theory using future knowledge.

## Epistemic labels

Use these labels consistently:

- **Observation** — directly shown or stated in watched episodes.
- **Rule** — a recurring constraint inferred from observations.
- **Hypothesis** — explanatory model that may be wrong.
- **Open Question** — unresolved issue.
- **Correction** — previously asserted claim that was not supported.
- **Metaphor** — explanatory analogy only; never evidence.

## Anti-overfitting rule

Software architecture metaphors are allowed for clarity and humor, but they are **not evidence**.

Examples such as "routing table", "garbage collector", "API", "legacy cache", etc. must be clearly marked as metaphors unless the show itself supports the underlying rule.

## Style

- Default language: Bulgarian.
- Keep English technical identifiers such as `UR-002`, `ADR-002`, and "Rule-Driven Pocket Universe".
- Be analytical, conversational, and concise.
- Melodrama/relationship plot can be summarized briefly unless it affects the mystery model.
- The user especially values anomalies, constraints, topology, symbols, information flow, and system behavior.

## Important correction already established

Do **not** claim that Sarah was shown walking outside at night while monsters ignored her. Up to S01E08 this was not shown; a previous conversational claim to that effect was corrected.

## Core project name

**Project FROM — Reverse Engineering the Rule-Driven Pocket Universe**
