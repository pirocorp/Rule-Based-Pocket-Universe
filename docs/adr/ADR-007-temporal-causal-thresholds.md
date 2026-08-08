# ADR-007 — Temporal / Causal Thresholds

**Статус:** Активно  
**Увереност:** ⭐⭐⭐⭐⭐ за Julie rope event; ⭐⭐⭐☆☆ за модела; ⭐☆☆☆☆ за свободно time travel.

## Контекст

До S03E07 `ruins + dungeon` се държеше като conditional spatial/containment node: Boyd можеше да достигне layer-а чрез запалена факла, а Randall/Julie hints подсказваха residual marked state.

S03E08 променя това. Julie остава физически в настоящето при руините, но преживява Martin/Boyd dungeon event-layer и хвърля въжето към Boyd в well сцената. Това обяснява старото rope mystery без да изисква Martin да е свободен.

## Решение

Проектът въвежда `Temporal / Causal Threshold Access` като отделна архитектурна ос:

- spatial node може да даде достъп до event-layer;
- event-layer може да има причинен ефект върху вече наблюдавана история;
- текущият най-предпазлив модел е self-consistent causal loop, не free time travel.

## Последствие

`Rule-Driven Pocket Universe` вече се мисли по три оси:

- spatial topology;
- information/contact channels;
- temporal/causal threshold events.

Това не отменя предишните spatial rules. То добавя guardrail: при бъдещи сцени с "минало", "спомен", "видение" или "реактивация" трябва да проверяваме дали има реална причинна връзка или само perceptual/historical payload.

## Guardrails

- Не приемаме, че миналото може да се променя.
- Не приемаме, че Julie може да избира произволно кога/къде да отиде.
- Не приемаме, че всички ruins/dungeon events са temporal.
- Не приемаме, че това доказва simulation, literal multiverse или единен controller.
