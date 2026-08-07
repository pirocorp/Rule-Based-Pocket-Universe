# Methodology

## Goal

Reverse engineer the fictional world as a black-box system without using future-episode knowledge.

## Pipeline

1. **Observation** — what was directly shown or explicitly said?
2. **Rule candidate** — what recurring constraint could explain it?
3. **Evidence** — which watched scenes support the candidate?
4. **Counter-evidence** — what does not fit?
5. **Confidence** — 1 to 5 stars.
6. **Open questions** — what remains unknown?
7. **Hypothesis impact** — does this strengthen/weaken a broader model?
8. **ADR update** — only if the architecture-level model changes.

## Confidence scale

- ⭐☆☆☆☆ — speculative.
- ⭐⭐☆☆☆ — weak support.
- ⭐⭐⭐☆☆ — plausible.
- ⭐⭐⭐⭐☆ — strong support.
- ⭐⭐⭐⭐⭐ — repeatedly and directly demonstrated.

## Anti-confirmation-bias rules

- A compelling theory is not a fact.
- A character's theory is not narration.
- Absence of an event can be evidence only when there was a clear opportunity for it to occur.
- If a future episode contradicts a rule, refactor or deprecate the rule instead of rescuing it.
- Distinguish a phenomenon's **behavior** from its **intent**.

## Software-architecture metaphors

Allowed as a second layer of discussion only.

Good:
> "Faraway Trees behave *like* routing shortcuts."

Bad:
> "Faraway Trees are routing tables, therefore the world is a simulation."

Metaphors help reason; they do not establish canon.

## Spoiler discipline

The project cutoff advances only when the user explicitly states a watched episode. At creation the cutoff is S01E08.
