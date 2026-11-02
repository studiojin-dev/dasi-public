# 다시 영단어 — 공개 단어 데이터 / Dasi English Vocab — open word data

[다시 영단어](https://studiojin.dev/ko/dasi/) 앱에 들어 있는 **영어 핵심 단어 팩(`en-ko-core`)** 데이터입니다. CC BY-SA 4.0 자료를 바탕으로 만든 2차 저작물이라 같은 라이선스로 공개합니다.

This is the **core English word pack (`en-ko-core`)** bundled in the [Dasi English Vocab](https://studiojin.dev/dasi/) app. It is adapted from CC BY-SA 4.0 material, so it is published under the same licence.

## 라이선스 / Licence

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — 전문은 [LICENSE](LICENSE). 앱의 소스 코드는 이 저장소에 없으며 이 라이선스의 대상이 아닙니다. / Full text in [LICENSE](LICENSE). The app's source code is not part of this repository and is not covered by this licence.

예문 중 Tatoeba 문장은 [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/)이며 문장별 작성자가 [`en-ko-core/attribution.tsv`](en-ko-core/attribution.tsv)에 있습니다. / Tatoeba sentences are CC BY 2.0 FR; their authors are listed per sentence in `attribution.tsv`.

## 출처 / Sources

- [Tatoeba](https://tatoeba.org) — CC BY 2.0 FR (예문 / example sentences)
- 한국어 위키낱말사전 / Korean Wiktionary, via [kaikki.org](https://kaikki.org/kowiktionary/) — CC BY-SA 4.0 (일부 뜻·예문·품사·IPA / some meanings, examples, parts of speech, IPA)
- [New General Service List, TOEIC Service List, Business Service List, New Academic Word List](https://www.newgeneralservicelist.com) — Browne, C., Culligan, B. & Phillips, J. — CC BY-SA 4.0 (표제어 선정·트랙 / word selection, tracks)
- [CEFR-J Vocabulary Profile 1.5](https://www.cefr-j.org) (Tono Lab, Tokyo University of Foreign Studies) — 인용 조건 / citation required (레벨 / levels)
- [Octanove Vocabulary Profile C1/C2](https://github.com/openlanguageprofiles/olp-en-cefrj) — CC BY-SA 4.0 (레벨 / levels)
- [FrequencyWords en_50k](https://github.com/hermitdave/FrequencyWords) (hermitdave, OpenSubtitles 2018) — CC BY-SA 4.0 (빈도 순서 / frequency order)

자세한 내용은 [`en-ko-core/ATTRIBUTION.md`](en-ko-core/ATTRIBUTION.md). / Details in `ATTRIBUTION.md`.

## 바꾼 점 / Changes

위 자료에서 표제어를 고르고 뜻·예문을 선별·요약·수정했습니다. 뜻과 예문의 대부분은 언어 모델(Claude Haiku·Sonnet, OpenAI Codex)로 새로 쓰고 검토했으며, 어느 예문이 어디서 왔는지는 `attribution.tsv` 의 `license` 열(`CC-BY-2.0-FR`, `CC-BY-SA-4.0`, `LLM-draft:<model>`)에 있습니다. 시험별 구분(학년·수능·토익·토플·GRE)은 공식 목록이 아닙니다.

Headwords were selected and meanings and examples were selected, summarised and edited from the sources above. Most meanings and example sentences were rewritten and checked with language models (Claude, Codex); the `license` column of `attribution.tsv` records where each example came from. Exam groupings are our own, not official lists.

## 파일 / Files

| 파일 | 내용 |
|---|---|
| `en-ko-core/words.jsonl` | 카드 한 줄에 하나: 표제어, 품사, IPA, 뜻(한국어), 예문(영·한), 레벨, 트랙 / one card per line |
| `en-ko-core/attribution.tsv` | 예문별 출처: 카드 id, 예문 번호, 라이선스, 원문 URL, 작성자 / per-example source and author |
| `en-ko-core/pack.json` | 팩 정보와 출처 목록 / pack manifest and credits |
| `en-ko-core/ATTRIBUTION.md` | 출처와 처리 과정 / sources and processing |

앱이 업데이트되어 데이터가 바뀌면 이 저장소도 함께 갱신합니다. / This repository is updated when the app's data changes.

© 2026 Studiojin (스튜디오진) · support@studiojin.dev
