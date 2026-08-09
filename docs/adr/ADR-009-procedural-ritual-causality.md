# ADR-009 — Procedural / Ritual Causality

**Статус:** Прието след S04E09  
**Граница:** S04E09

## Контекст

До S04E08 моделът вече съдържаше sacrifice/rebirth substrate, Bottle Tree melody, blood/ingestion payloads, corpse reanimation и class-specific protections. S04E09 добавя директно твърдение от Man in Yellow/Sophia-form, че мястото е built on ritual и че при ritual-и **как** се прави нещо може да е толкова важно, колкото **какво** се прави.

Същият епизод дава няколко operational examples:

- Clara не просто "помага" на MIY, а е активирана чрез bargain/blood-pact language.
- Fatima payload-ът минава през Clara и кръвта й, не директно от MIY.
- Tabitha разбира, че само тя и Jade трябва да слязат за костите.
- Sophia/MIY реагира негативно на тази промяна в участниците.
- rope ladder sabotage прекъсва не само целта, а процедурата за достигане до bones target-а.
- Jade и Tabitha физически намират костите, което прави rescue/bones line-а проверим operational target.

## Решение

Третираме procedural / ritual causality като first-class architectural rule family:

> Във FROM крайният резултат не е достатъчен за описание на правило. Участниците, редът, мястото, предметите, думите, кръвта, музиката, route-ът и методът могат да са част от самото causal условие.

Това не заменя Rule-Driven Pocket Universe модела. Прави го по-строг: правилата вече трябва да записват не само input/output, а и procedure.

## Последствия

- При нови правила записваме `actors`, `location`, `objects`, `sequence`, `words/sound`, `blood/body material` и `route`, когато са релевантни.
- Не приемаме, че два еднакви крайни резултата имат еднаква причина.
- Failed tests вече трябва да се проверяват procedural: дали тестът повтаря правилния метод, или само имитира outcome-а.
- Bottle Tree, bones rescue, blood payloads, corpse reanimation и talisman/totem effects трябва да се проследяват с procedure metadata.
- `Tabitha + Jade` вече е потенциално важна ritual configuration, не само character pairing.

## Guardrails

- Това не доказва, че всяко явление във FROM е ритуал.
- Това не доказва, че Man in Yellow казва истината във всички детайли.
- Това не доказва, че Clara е знаела всичко от началото; доказано е activation/bargain usage в S04E09.
- Това не доказва, че bones-rescue процедурата ще работи.
- Това не доказва, че всички правила са човешки разбираеми или възпроизводими.
