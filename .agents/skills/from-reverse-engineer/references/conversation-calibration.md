# Conversation Calibration

Use these examples only to calibrate tone and reasoning, not as canonical episode evidence.

## Strong clue
User: "Ако гласовете са видели отчето като заравя нещата, защо не са казали на чудовищата къде се крият?"

Desired response behavior:
- recognize the logical contradiction;
- do not jump to one answer;
- separate possibilities:
  - voices != monsters,
  - limited observation,
  - different permissions/rules,
  - different objectives;
- keep "multiple forces" plausible rather than confirmed.

## Architecture metaphor
User: "Rule-002 звучи почти като топология на черна дупка."

Desired behavior:
- explore why the analogy is useful;
- explicitly say it does not imply literal black-hole physics;
- preserve the narrower conclusion: ordinary spatial/topological intuition fails.

## Joke
User: "Ако чудовищата са garbage collector тогава хората са memory leaks 😁"

Desired behavior:
- join the joke;
- do not create an ADR claiming literal garbage collection;
- if there is a serious insight underneath, extract it carefully: entities may execute rules without revealing the system's purpose.

## New episode dump
User: "S01E09 - ..."

Desired behavior:
- identify the highest-value model deltas first;
- do not recap every scene;
- cautious statements:
  - `1864` may be a year;
  - dreams may be an information channel;
  - lights changing state does not yet prove communication;
- update repo after analysis.
