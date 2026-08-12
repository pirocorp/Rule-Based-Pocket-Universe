# Проект FROM — обратен инженеринг на Rule-Driven Pocket Universe

Дневник за обратен инженеринг, дисциплиниран от спойлери и ориентиран към доказателства, за телевизионния сериал **FROM**.

**Текуща граница на знанието:** **S04E10**

**Статус на гледане:** **Сезон 4, епизод 10**

Основният работен модел след S04E10 е:

> **FROM изглежда като Rule-Driven Pocket Universe, в който поне две opposing agencies действат върху една shared rule system, а хората могат да променят system-level outcome само ако изпълнят правилната процедура.**

Това заключение има три отделни части:

- **Shared rule system:** топологията, светлината, талисманите, entity classes, ритуалите и spatial nodes имат ограничения, които не зависят само от желанията на една entity.
- **Opposing agencies:** Boy in White и Man in Yellow са директно противопоставени, но не са доказано единствените сили и не установяват проста good/evil космология.
- **Procedural human agency:** хората не променят големите резултати само чрез намерение или чрез постигане на сходен краен вид; значение могат да имат точните участници, ред, място, objects, route, думи, музика, кръв и timing.

`Правилната процедура` тук е архитектурен извод за важните system-level намеси, не твърдение, че всяко действие във FROM е ритуал.

Проектът третира света като черна кутия. Събираме наблюдения, извличаме правила, проследяваме увереност, тестваме хипотези срещу следващи епизоди и рефакторираме или отхвърляме идеи, когато доказателствата се променят.

## Основна директива

**Observation → Rule → Evidence → Confidence → Open Questions → Hypothesis**

Не започвайте с теория и не принуждавайте наблюденията да й пасват.

## Картата на хранилището

- [`AGENTS.md`](AGENTS.md) — инструкции за Codex/AI агенти, работещи в това хранилище.
- [`CURRENT_STATE.md`](CURRENT_STATE.md) — кратък моментен образ на това, което се вярва след S04E10.
- [`docs/methodology.md`](docs/methodology.md) — методология на анализа и правила срещу пренатягате на модела.
- [`docs/adr/`](docs/adr/) — архив на архитектурни решения за текущия модел.
- [`docs/rules/`](docs/rules/) — идентифицирани правила за вселената, обектите и знанието.
- [`docs/hypotheses/`](docs/hypotheses/) — активни и конкуриращи се хипотези.
- [`docs/episodes/`](docs/episodes/) — бележки от епизод на епизод.
- [`docs/season-reviews/`](docs/season-reviews/) — season-boundary model reviews преди следващия сезон.
- [`docs/open-questions.md`](docs/open-questions.md) — неразрешени въпроси.
- [`docs/evidence-ledger.md`](docs/evidence-ledger.md) — важни доказателства и увереност.
- [`docs/spatial-nodes.md`](docs/spatial-nodes.md) — регистър на пространствени възли и слоеве.
- [`docs/maps/town-layout-map.md`](docs/maps/town-layout-map.md) — помощна карта/артефакт за town layout и spatial node grouping.
- [`docs/handoff/`](docs/handoff/) — траен контекст за продължаване с ChatGPT/Codex.
- [`docs/templates/`](docs/templates/) — шаблони за бъдещи актуализации.
- [`assets/`](assets/) — скрийншоти, предоставени по време на анализа.

## Текущ основен модел

Точката на четене за списъка по-долу е: **правилата са общият substrate; агенциите се борят за outcome-а; хората получават реална agency, когато открият и изпълнят приложимата процедура.**

1. **Entry/exit topology:** влизането е свързано с падналото дърво, а пътищата се връщат обратно към града.
2. **Re-entry вече е demonstrated:** след apparent outside transition-а Tabitha отново е прихваната през fallen-tree boundary и линейката попада във FROM.
3. **Информационната граница не съвпада с физическата:** Elgin/Miranda/Tabitha показват pre-entry, cross-boundary и post-exit contact линии.
4. **Инфраструктурата/медиите са interface layer:** радио, телефон, jukebox, music box, лампи, ток и Polaroid camera могат да носят payload-и, context-sensitive намеса или spatial/action instructions; S04E08 почти директно връзва `Thomas` phone voice-а с Man in Yellow lure, а S04E09 използва old photo/Polaroid evidence, за да разобличи Sophia-form-а.
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
26. **Man in Yellow е почти сигурният S01E10 radio voice/source:** връзката е много силна, а S04E08 почти директно връзва `Thomas` familiar voice channel-а с MIY, когато гласът води Tabitha до caravan/RV, където той я чака.
27. **Entity Form-Shifting / Avatar Infiltration:** S04E01 визуално показва Man in Yellow да приема/преминава в образа на Sophia; S04E09 добавя потвърден constraint, че MIY може да приема само форми на хора, умрели във FROM.
28. **Story Walker self-consistency е по-силна:** Man in Yellow разпознава Julie като temporal visitor и повтаря, че вече разказана история не може да се промени.
29. **Нови пристигащи могат да имат neurological disruption:** бащата на Sophia получава seizure-like episode след падналото дърво и катастрофира в града; това не е универсално правило, но е важен entry clue.
30. **Convergent information channels:** Sara voices, kimono/Polaroid, children guidance, Thomas voice, Boy in White, Julie threshold access и Man in Yellow се концентрират върху ключови nodes/events; това е convergence clue, не доказателство за един controller.
31. **Knowledge has cost вече е staged message:** тялото на Jim е поставено в хамбара с надпис `Knowledge comes at a cost`, което силно подсилва Man in Yellow като hostile enforcer около forbidden knowledge, без да доказва универсално правило за всяко търсене на отговори.
32. **Story Walking е повторяемо и опасно:** Julie се връща в ruins node-а и достига RV/arrival chapter, където чудовище почти я хваща. Past/event chapters могат да я застрашат, но свободно променяемо минало още не е доказано.
33. **Lake of Tears става actionable candidate:** Ethan вижда образа на Jim, който го насочва към `Lake of Tears`; familiar face не доказва source identity, но старият quest/narrative елемент вече е spatial target.
34. **Bottle Tree route validity е state-dependent:** Boy in White предупреждава, че дървото може вече да не отведе Tabitha до lighthouse-а; `Bottle Tree -> lighthouse` е грешно като фиксирано правило.
35. **Boy in White може да е shared manifestation:** Tabitha и Henry го виждат едновременно, което отслабва чисто личната hallucination версия, но не доказва добронамереност.
36. **Man in Yellow не е доказан controller на всичко:** apparent surprise на Sophia-form към гарваните отваря `Non-Uniform Agency` clue; възможно е corvid/bird line-ът да е независим или поне не напълно под негов контрол.
37. **Victor има recognition/fear response към Man in Yellow imagery:** S04E04 вече свързва това с Victor-era massacre и Man in Yellow human consumption около Miranda/жертвите.
38. **Sara voice channel може да бъде използван/активиран от Man in Yellow:** S04E04 силно подсилва връзката чрез Sophia-form ritual и water-command test, но не доказва, че всички Sara voices са Man in Yellow.
39. **Story Walker self-consistency получава отрицателен тест:** Julie haircut-ът връзва future-Julie със същата линия, а failed bookmark experiment отслабва freely editable history.
40. **Lake of Tears става experiment target:** Ethan използва ранена птица като възможен тест за healing/fixing функция, без node-ът или ефектът да са доказани.
41. **Jade visions се refactor-ват към prior-incarnation memory:** S04E05 подсилва, че фигурите, които Jade вижда, са негови предишни превъплъщения/цикли, а провалите им често минават през хората в града, не през стандартните чудовища.
42. **Jade vision вече има physical confirmation layer:** S04E06 hidden-door check-ът показва, че поне част от Jade false-state/vision информацията съдържа обективно вярна скрита spatial information.
43. **Lake / cabin zone има отделен hostile entity class:** fake corpses/dolls/effigies излизат от езерото, нападат в cabin zone-а и могат да бъдат спрени чрез totem/stake/impalement-like physical action; това не ги прави standard monsters и не доказва универсална iron weakness.
44. **Forest Fear Assimilation е силна hypothesis:** куклите на Tabitha и Nathan/cicada връзката подкрепят идеята, че страхове/кошмари на мъртви хора могат да се материализират в гората, но това остава in-universe theory, не confirmed law.
45. **Man in Yellow blood-payload вече има Henry effect sequence:** Sophia-form поставя собствена кръв в питието на Henry, S04E07 добавя altered/immersive false-state, а S04E08 продължава Henry false-reality / bad-LSD framing-а; причинността остава candidate, но вече е много по-подозрителна.
46. **Donna S04E06 е near-death, не death:** тя получава cardiac arrest и е реанимирана, което отваря тестов въпрос дали клинична смърт/връщане има значение във FROM.
47. **Man in Yellow може да reanimate-ва corpse body:** S04E07 egg/ritual-like action върху Roger corpse води до animated body; това не е доказано true resurrection.
48. **Totem/spear effects са class-specific:** S04E07 показва, че totem/spear-like weapon спира Roger corpse, но не стандартно чудовище; S04E08 добавя, че MIY/monster side може да weaponize-ва uncertainty около тези правила.
49. **Fatima-Smiley residual link става operational:** Fatima изглежда възприема/влияе през Smiley channel-а и нарушава атаката срещу Kenny; S04E08 добавя post-incubation transformation/body-change candidate, без да доказва standard monster conversion.
50. **Brown car на Man in Yellow е physical artifact:** колата вече е намерена/проверена и съдържа човешки зъби, което подсилва human-consumption/trophy/ritual-material въпросите.
51. **Yellow suit има persistent significance:** MIY си прибира жълтия костюм; след Victor recognition line-а това става object-status clue, не просто wardrobe.
52. **Knowledge-cost вече включва preemptive sabotage:** MIY знае за плана да се изровят костите, което прави children bones/rescue line-а protected high-value target candidate.
53. **Procedural / Ritual Causality:** S04E09 директно казва, че мястото е built on ritual и че how matters as much as what; точната процедура може да е толкова важна, колкото крайният резултат.
54. **Clara е MIY sleeper asset:** сделката й е активирана в S04E09, което добавя human intelligence/action channel към MIY, без да доказва omniscience.
55. **Tabitha + Jade изглеждат правилната ritual configuration:** реакцията на MIY/Sophia към промяната на плана подсказва, че той се тревожи от правилните участници/процедура, не само от копаенето.
56. **Костите са physical confirmation/protected target:** Jade и Tabitha стигат до костите, а чудовищата се появяват/противодействат; това не доказва още, че rescue procedure работи.
57. **Правилата са по-важни от всяка отделна единица.**
58. **Standard monsters имат direct-light restriction:** S04E10 false-night им позволява surface action посред ден, но връщането на слънчевата светлина ги принуждава да се оттеглят.
59. **Bottle Tree е structural node:** премахването му / bones procedure line-ът води до false-night, земетресение и world-state destabilization.
60. **MIY атакува protection infrastructure:** талисманите са събрани и пуснати през Faraway Tree; това е removal/relocation, не доказано унищожение на правилото.
61. **Fatima вече е post-incubation monster-like altered state:** Smiley я нарича "Mother", тя усеща чудовищата и може да го отблъсне, но не е доказано standard monster conversion.
62. **Boy in White и Man in Yellow са директно opposed agents:** S04E10 доказва опозиция, но не доказва проста good/evil космология.

## Политика за спойлери

Никога не използвайте информация от епизоди след текущата граница на знанието, освен ако потребителят не каже изрично, че ги е гледал и границата не бъде преместена.

При създаване на хранилището границата беше **S01E08**; текущата граница се чете от `project.json` и `CURRENT_STATE.md`.
