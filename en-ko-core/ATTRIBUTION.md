# en-ko-core — 출처와 라이선스

이 팩의 글(뜻·예문·레벨)은 아래 공개 자료에서 **선별·요약·정리(수정)** 해 파생했다. 가장 제한적인 조건(CC BY-SA 4.0)을 따르므로 **팩 자체도 CC BY-SA 4.0** 으로 배포한다. 앱 코드는 별개다.

- **Tatoeba English sentences (detailed)** — CC-BY-2.0-FR — Tatoeba (https://tatoeba.org), CC BY 2.0 FR. 문장마다 작성자(username) 표기 필요 → attribution.tsv
- **Tatoeba Korean sentences (detailed)** — CC-BY-2.0-FR — Tatoeba (https://tatoeba.org), CC BY 2.0 FR. 문장마다 작성자(username) 표기 필요 → attribution.tsv
- **Tatoeba English–Korean links** — CC-BY-2.0-FR — Tatoeba (https://tatoeba.org), CC BY 2.0 FR. 문장마다 작성자(username) 표기 필요 → attribution.tsv
- **ko.wiktionary English entries (kaikki.org wiktextract)** — CC-BY-SA-4.0 OR GFDL-1.3-or-later — 한국어 위키낱말사전 (https://ko.wiktionary.org) 기여자, wiktextract/kaikki.org (https://kaikki.org/kowiktionary/). CC BY-SA 4.0 — 파생 팩도 CC BY-SA 로 공개해야 한다
- **New General Service List 1.2 (stats)** — CC-BY-SA-4.0 — Browne, C., Culligan, B. & Phillips, J. New General Service List project (https://www.newgeneralservicelist.com), CC BY-SA 4.0
- **TOEIC Service List 1.2 (stats)** — CC-BY-SA-4.0 — Browne, C., Culligan, B. & Phillips, J. New General Service List project (https://www.newgeneralservicelist.com), CC BY-SA 4.0
- **Business Service List 1.2 (stats)** — CC-BY-SA-4.0 — Browne, C., Culligan, B. & Phillips, J. New General Service List project (https://www.newgeneralservicelist.com), CC BY-SA 4.0
- **New Academic Word List 1.2 (lemmatized)** — CC-BY-SA-4.0 — Browne, C., Culligan, B. & Phillips, J. New General Service List project (https://www.newgeneralservicelist.com), CC BY-SA 4.0
- **CEFR-J Vocabulary Profile 1.5 (A1–B2)** — LicenseRef-CEFR-J (citation required; research/education/commercial OK) — CEFR-J Vocabulary Profile 1.5 (Tono Lab, Tokyo University of Foreign Studies, https://www.cefr-j.org), openlanguageprofiles/olp-en-cefrj 미러 CSV 사용 (https://github.com/openlanguageprofiles/olp-en-cefrj). 인용 필수
- **Octanove Vocabulary Profile C1/C2 1.0** — CC-BY-SA-4.0 — Octanove Vocabulary Profile C1/C2 (https://github.com/openlanguageprofiles/olp-en-cefrj), CC BY-SA 4.0
- **FrequencyWords en_50k (OpenSubtitles 2018)** — CC-BY-SA-4.0 — hermitdave/FrequencyWords (https://github.com/hermitdave/FrequencyWords), OpenSubtitles 기반, CC BY-SA 4.0

예문별 출처: `attribution.tsv` (wordId, example, 라이선스, 학습 언어 문장 URL, 작성자, 모국어 문장 URL, 작성자). Tatoeba 문장은 CC BY 2.0 FR 이고 작성자가 비어 있으면 Tatoeba 가 작성자를 공개하지 않은 문장(\N)이다. 위키낱말사전 예문은 CC BY-SA 4.0 이며 항목 URL 로 표기한다.

## LLM 초안

공개 자료로 채우지 못한 예문과 일부 카드의 뜻·IPA 는 claude-haiku-5-5 초안이다 (사람 검수 전). 예문은 `attribution.tsv` 의 license `LLM-draft:claude-haiku-5-5`, 새 카드는 `tags` 의 `llm-gloss` 로 표시한다.

## 심사·수정

카드 전체를 claude-sonnet-5-5 이 심사해(`pack grade`) 품사·IPA·뜻·예문을 고쳤다(`pack grade-apply`, 사람 검수 전). 고친 뜻을 가진 카드는 `tags` 의 `llm-gloss`, 새로 쓴 예문은 `attribution.tsv` 의 license `LLM-draft:claude-sonnet-5-5` 로 표시한다. 원문을 유지한 예문의 출처 줄은 그대로이며, 번역만 바뀐 예문은 모국어 출처 칸을 비웠다.

## Tracks (school levels, tests)

The elementary / middle / high-school·CSAT / TOEIC / TOEFL / GRE tracks are not official word lists. TOEIC uses the NGSL and the TOEIC Service List (TSL); TOEFL adds the New Academic Word List (NAWL); the rest were assigned by a language model (Claude Sonnet) from each word's frequency band, CEFR-like level and meaning.
