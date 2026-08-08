# Проект FROM — обратен инженеринг на Rule-Driven Pocket Universe

Дневник за обратен инженеринг, дисциплиниран от спойлери и ориентиран към доказателства, за телевизионния сериал **FROM**.

**Текуща граница на знанието:** **S03E10**

**Статус на гледане:** **Сезон 3, епизод 10**

Основната работна хипотеза е умишлено широка:

> **FROM може да е Rule-Driven Pocket Universe: затворена или топологично необичайна среда, чиито обекти и явления действат според откриваеми правила.**

Проектът третира света като черна кутия. Събираме наблюдения, извличаме правила, проследяваме увереност, тестваме хипотези срещу следващи епизоди и рефакторираме или отхвърляме идеи, когато доказателствата се променят.

## Основна директива

**Observation → Rule → Evidence → Confidence → Open Questions → Hypothesis**

Не започвайте с теория и не принуждавайте наблюденията да й пасват.

## Картата на хранилището

- [`AGENTS.md`](AGENTS.md) — инструкции за Codex/AI агенти, работещи в това хранилище.
- [`CURRENT_STATE.md`](CURRENT_STATE.md) — кратък моментен образ на това, което се вярва след S03E10.
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
4. **Инфраструктурата/медиите са interface layer:** радио, телефон, jukebox, music box, лампи, ток и Polaroid camera могат да носят payload-и, context-sensitive намеса или spatial/action instructions.
5. **Real-Time Hidden-State Access:** radio/Thomas voice каналите знаят текущи или incoming/transit състояния, без source identity да е доказана.
6. **Топологията е слоеста:** град, гора, Faraway/Bottle Trees, подземия, руини + факла, lighthouse/tower, cabin cluster, motel/pool anomaly и apparent outside bridge са отделни spatial/contact nodes.
7. **Чудовищата са strategic agents:** освен нощен лов, те използват ресурси, капани, prolonged suffering, bargain/hostage-like leverage и psychological warfare.
8. **Чудовищата имат origin account:** S03E10 свързва ги с child sacrifice и bargain за вечен живот; това прави former-human/post-human линията много силна.
9. **Monster body death не е permanent death:** blood/worm transfer убива Smiley body instance-а, но S03E10 показва rebirth през Fatima condition-а.
10. **Cicada / Music-Box / Rhyme Threat Subsystem:** sleep е attack surface, не requirement; S02E10 показва stop condition за active three-person captivity instance, но S03E10 Randall още има cicada problem, така че residue/marked-state линията остава жива.
11. **Temporal / Causal Threshold Access:** S03E08 показва Julie да преживява dungeon/Martin/Boyd event-layer и да хвърля въжето към Boyd; S03E10 добавя Story Walker framing и future-Julie/Jim scene. Това е силен self-consistent causal-loop candidate, не свободно time-travel правило.
12. **Символът има historical/tunnel/children/root link:** Christopher и Jade са symbol-exposure cases, а S03E08 origin account свързва децата, stones, hope, roots, символа и Faraway Tree.
13. **Tabitha/Jade са reincarnating rescuers:** S03E10 refactor-ва role recurrence-а: Miranda/Christopher са предишни превъплъщения на Tabitha/Jade, а едно от жертваните деца е било тяхно.
14. **Conditional / unsafe tree routing:** Bottle Tree не е прост фиксиран route; Tabitha стига до lighthouse, а Dale се оказва вграден в pool wall.
15. **Bottle Tree numbers са melody/memory key:** числата вече са доказано usable като музикална последователност, която отключва children/reincarnation memory; routing функцията на tree node-а остава отделен въпрос.
16. **External Template / Internal Echo:** outside Bottle Tree и гривната са physical object/structure bridges между apparent outside world и FROM/Victor family line.
17. **Town As Functional Facade / Architectural Incoherence:** motel sign + pool без видим motel building вече се разширява чрез Acosta към diner/post-office/travel-agency странности.
18. **Fatima condition е monster rebirth / incubation vector:** "baby not yours" се оказва Smiley rebirth. Human blood/flesh е силно свързано с gestation/regeneration, но adult-monsters-as-vampire-feeders остава нискоуверена хипотеза.
19. **Object / Voice Interface Candidate е refactor-нат:** Jasper остава важен artifact/memory trigger, но S03E08 сочи, че Boy in White, не Jasper, е говорил на Christopher.
20. **Monster daytime caveat:** чудовищата са активни на повърхността нощем, но S03E06 показва, че могат да са будни/интерактивни под земята през деня.
21. **Tabitha long-horizon contact:** детският й кошмар за forest settlement/red stones подсилва pre-arrival contact години преди physical entry.
22. **Polaroid / Photographic Instruction Interface:** камерата сама произвежда повтарящи се visual/action payload-и, които водят Elgin към root cellar / hidden room и към containment action спрямо Fatima.
23. **Kimono manifestation вече не е Elgin-only:** Fatima също я вижда, а S03E10 я свързва директно с Smiley rebirth/monster immortality subsystem-а.
24. **`Anghkooey` означава "remember":** думата е memory command/key към reincarnation/rescue subsystem-а, не вече напълно неизвестен звук.
25. **Julie е Story Walker candidate:** може да посещава "стари глави" и да участва causal в тях; финалът подсилва self-consistent history, не свободно променяемо минало.
26. **Man in Yellow е почти сигурният S01E10 radio voice/source:** връзката е много силна, но той не е доказан архитект или controller на всички феномени.
27. **Convergent information channels:** Sara voices, kimono/Polaroid, children guidance, Thomas voice, Boy in White, Julie threshold access и Man in Yellow се концентрират върху ключови nodes/events; това е convergence clue, не доказателство за един controller.
28. **Правилата са по-важни от всяка отделна единица.**

## Политика за спойлери

Никога не използвайте информация от епизоди след текущата граница на знанието, освен ако потребителят не каже изрично, че ги е гледал и границата не бъде преместена.

При създаване на хранилището границата беше **S01E08**; текущата граница се чете от `project.json` и `CURRENT_STATE.md`.
