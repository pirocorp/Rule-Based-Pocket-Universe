# Проект FROM — обратен инженеринг на Rule-Driven Pocket Universe

Дневник за обратен инженеринг, дисциплиниран от спойлери и ориентиран към доказателства, за телевизионния сериал **FROM**.

**Текуща граница на знанието:** **S03E07**

**Статус на гледане:** **Сезон 3, епизод 7**

Основната работна хипотеза е умишлено широка:

> **FROM може да е Rule-Driven Pocket Universe: затворена или топологично необичайна среда, чиито обекти и явления действат според откриваеми правила.**

Проектът третира света като черна кутия. Събираме наблюдения, извличаме правила, проследяваме увереност, тестваме хипотези срещу следващи епизоди и рефакторираме или отхвърляме идеи, когато доказателствата се променят.

## Основна директива

**Observation → Rule → Evidence → Confidence → Open Questions → Hypothesis**

Не започвайте с теория и не принуждавайте наблюденията да й пасват.

## Картата на хранилището

- [`AGENTS.md`](AGENTS.md) — инструкции за Codex/AI агенти, работещи в това хранилище.
- [`CURRENT_STATE.md`](CURRENT_STATE.md) — кратък моментен образ на това, което се вярва след S03E07.
- [`docs/methodology.md`](docs/methodology.md) — методология на анализа и правила срещу пренатягате на модела.
- [`docs/adr/`](docs/adr/) — архив на архитектурни решения за текущия модел.
- [`docs/rules/`](docs/rules/) — идентифицирани правила за вселената, обектите и знанието.
- [`docs/hypotheses/`](docs/hypotheses/) — активни и конкуриращи се хипотези.
- [`docs/episodes/`](docs/episodes/) — бележки от епизод на епизод.
- [`docs/open-questions.md`](docs/open-questions.md) — неразрешени въпроси.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — важни доказателства и увереност.
- [`docs/spatial-nodes.md`](docs/spatial-nodes.md) — регистър на пространствени възли и слоеве.
- [`docs/maps/town-layout-map.md`](docs/maps/town-layout-map.md) — помощна карта/артефакт за town layout и spatial node grouping.
- [`docs/handoff/`](docs/handoff/) — траен контекст за продължаване с ChatGPT/Codex.
- [`docs/templates/`](docs/templates/) — шаблони за бъдещи актуализации.
- [`assets/`](assets/) — скрийншоти, предоставени по време на анализа.

## Текущ основен модел

1. **Entry/exit topology:** влизането е свързано с падналото дърво, а пътищата се връщат обратно към града.
2. **Re-entry вече е demonstrated:** след apparent outside transition-а Tabitha отново е прихваната през fallen-tree boundary и линейката попада във FROM.
3. **Информационната граница не съвпада с физическата:** Elgin/Miranda/Tabitha показват pre-entry, cross-boundary и post-exit contact линии.
4. **Инфраструктурата/медиите са interface layer:** радио, телефон, jukebox, music box, лампи, ток и Polaroid camera могат да носят payload-и, context-sensitive намеса или spatial instructions.
5. **Real-Time Hidden-State Access:** radio/Thomas voice каналите знаят текущи или incoming/transit състояния, без source identity да е доказана.
6. **Топологията е слоеста:** град, гора, Faraway/Bottle Trees, подземия, руини + факла, lighthouse/tower, cabin cluster, motel/pool anomaly и apparent outside bridge са отделни spatial/contact nodes.
7. **Чудовищата са strategic agents:** освен нощен лов, те използват ресурси, капани, prolonged suffering, bargain/hostage-like leverage и psychological warfare.
8. **Чудовищата имат human-linked/post-human biology:** аутопсията показва човешка анатомия и аномална вътрешност, но former-human механизмът не е доказан.
9. **Blood/worm transfer е уникално доказана monster vulnerability:** едно чудовище умира след direct transfer; bile bullets не възпроизвеждат ефекта.
10. **Cicada / Music-Box / Rhyme Threat Subsystem:** sleep е attack surface, не requirement; S02E10 показва stop condition за active three-person captivity instance, но S03E07 Randall/Julie hints подсказват residual marked/connected state.
11. **Символът има historical/tunnel/children link:** Christopher и Jade са symbol-exposure cases, а символът се връзва с подземния слой и децата.
12. **Miranda/Tabitha и Christopher/Jade подсилват role recurrence:** това е функционален pattern candidate, не доказан time loop, destiny или reincarnation.
13. **Conditional / unsafe tree routing:** Bottle Tree не е прост фиксиран route; Tabitha стига до lighthouse, а Dale се оказва вграден в pool wall.
14. **Bottle Tree numbers:** `1864` и `2659` са structured four-digit data, а S03E06 добавя same-number-set, repeated-number и mirrored/reversed-digit clues; значението остава unknown.
15. **External Template / Internal Echo:** outside Bottle Tree и гривната са physical object/structure bridges между apparent outside world и FROM/Victor family line.
16. **Town As Functional Facade / Architectural Incoherence:** motel sign + pool без видим motel building вече се разширява чрез Acosta към diner/post-office/travel-agency странности.
17. **Fatima Pregnancy / Appetite Anomaly:** вече е pregnancy-like anomalous condition без видим fetus при scan-а, body/craving escalation и physical danger to others; без monster-pregnancy или possession заключение.
18. **Object / Voice Interface Candidate:** Jasper/dummy около Christopher вече е физически retrieve-нат actionable object, но говоренето му остава Victor memory/story.
19. **Monster daytime caveat:** чудовищата са активни на повърхността нощем, но S03E06 показва, че могат да са будни/интерактивни под земята през деня.
20. **Tabitha long-horizon contact:** детският й кошмар за forest settlement/red stones подсилва pre-arrival contact години преди physical entry.
21. **Polaroid / Photographic Instruction Interface:** камерата сама произвежда изображение, което води Elgin към root cellar / hidden room node.
22. **Правилата са по-важни от всяка отделна единица.**

## Политика за спойлери

Никога не използвайте информация от епизоди след текущата граница на знанието, освен ако потребителят не каже изрично, че ги е гледал и границата не бъде преместена.

При създаване на хранилището границата беше **S01E08**; текущата граница се чете от `project.json` и `CURRENT_STATE.md`.
