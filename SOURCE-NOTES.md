# Oak National Academy – KS1 to KS4 (GCSE) lesson quizzes

- Source: Oak National Academy Open API – https://open-api.thenational.academy/ (lesson pages: https://www.thenational.academy/teachers/lessons/<lesson-slug>, stored per row in `sourceUrl`)
- Licence: Open Government Licence v3.0 (OGL) – https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/ (compatible with CC BY 4.0; commercial use allowed with attribution; no ShareAlike)
- Questions: 24,749 (category: `ks1`, `ks2`, `ks3`, `gcse` for Key Stage 4; `keyStage` field = ks1..ks4)
- Explanations: no (Oak quizzes have none; `explanationStatus: "missing"`)
- Country / curriculum: England – National Curriculum, KS1 (Years 1–2), KS2 (Years 3–6), KS3 (Years 7–9), KS4 / GCSE (Years 10–11)
- Imported: 2026-11-03 with `oak_import.py` (Open API v1), all 17 Oak subjects × KS1–KS4 checked

| Subject | Key stage | Category | Folder | Questions |
|---|---|---|---|---|
| Citizenship | KS3 (Years 7–9, ages 11–14) | `ks3` | `citizenship/ks3/` | 356 |
| Citizenship | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `citizenship/ks4/` | 868 |
| Computing | KS1 (Years 1–2, ages 5–7) | `ks1` | `computing/ks1/` | 103 |
| Computing | KS2 (Years 3–6, ages 7–11) | `ks2` | `computing/ks2/` | 604 |
| Computing | KS3 (Years 7–9, ages 11–14) | `ks3` | `computing/ks3/` | 512 |
| Computing | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `computing/ks4/` | 1,385 |
| Cooking and Nutrition | KS1 (Years 1–2, ages 5–7) | `ks1` | `cooking-and-nutrition/ks1/` | 51 |
| Cooking and Nutrition | KS2 (Years 3–6, ages 7–11) | `ks2` | `cooking-and-nutrition/ks2/` | 97 |
| Cooking and Nutrition | KS3 (Years 7–9, ages 11–14) | `ks3` | `cooking-and-nutrition/ks3/` | 64 |
| Design and Technology | KS1 (Years 1–2, ages 5–7) | `ks1` | `design-and-technology/ks1/` | 188 |
| Design and Technology | KS2 (Years 3–6, ages 7–11) | `ks2` | `design-and-technology/ks2/` | 471 |
| Design and Technology | KS3 (Years 7–9, ages 11–14) | `ks3` | `design-and-technology/ks3/` | 318 |
| Design and Technology | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `design-and-technology/ks4/` | 556 |
| History | KS1 (Years 1–2, ages 5–7) | `ks1` | `history/ks1/` | 559 |
| History | KS2 (Years 3–6, ages 7–11) | `ks2` | `history/ks2/` | 738 |
| History | KS3 (Years 7–9, ages 11–14) | `ks3` | `history/ks3/` | 1,032 |
| History | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `history/ks4/` | 426 |
| Math | KS1 (Years 1–2, ages 5–7) | `ks1` | `math/ks1/` | 551 |
| Math | KS2 (Years 3–6, ages 7–11) | `ks2` | `math/ks2/` | 1,390 |
| Math | KS3 (Years 7–9, ages 11–14) | `ks3` | `math/ks3/` | 1,267 |
| Math | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `math/ks4/` | 1,213 |
| Physical Education | KS1 (Years 1–2, ages 5–7) | `ks1` | `physical-education/ks1/` | 1,211 |
| Physical Education | KS2 (Years 3–6, ages 7–11) | `ks2` | `physical-education/ks2/` | 2,299 |
| Physical Education | KS3 (Years 7–9, ages 11–14) | `ks3` | `physical-education/ks3/` | 1,746 |
| Physical Education | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `physical-education/ks4/` | 1,442 |
| RSHE (PSHE) | KS1 (Years 1–2, ages 5–7) | `ks1` | `rshe-pshe/ks1/` | 104 |
| RSHE (PSHE) | KS2 (Years 3–6, ages 7–11) | `ks2` | `rshe-pshe/ks2/` | 227 |
| RSHE (PSHE) | KS3 (Years 7–9, ages 11–14) | `ks3` | `rshe-pshe/ks3/` | 369 |
| RSHE (PSHE) | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `rshe-pshe/ks4/` | 204 |
| Science | KS1 (Years 1–2, ages 5–7) | `ks1` | `science/ks1/` | 370 |
| Science | KS2 (Years 3–6, ages 7–11) | `ks2` | `science/ks2/` | 1,666 |
| Science | KS3 (Years 7–9, ages 11–14) | `ks3` | `science/ks3/` | 1,297 |
| Science | KS4 / GCSE (Years 10–11, ages 14–16) | `gcse` | `science/ks4/` | 1,065 |

**Not included (Oak marks every lesson `restricted`, i.e. not OGL-compatible, so no questions can be used):** English, Geography, Religious Education, Art and Design, Music, French, German, Spanish.

Files: `oak/<subject>/<ks1|ks2|ks3|ks4>/<unit>.json`, one Kankoor-style JSON array per Oak unit. `difficulty` is `easy` for starter-quiz and `medium` for exit-quiz questions; `tags` record which quiz and lesson the question came from. Question and option text is kept exactly as Oak wrote it (maths uses `$$…$$` LaTeX; `{{}}` blanks shown as `____`).

## What was kept / left out

Kept: single-answer, text-only multiple-choice questions from starter and exit quizzes of lessons that Oak's `check-restricted` endpoint marks **ogl-compatible**.
Left out: every lesson marked `restricted` (third-party / not openly licensed), short-answer, match and order questions, questions needing an image, audio or video, questions with several or no correct answers, broken rows (duplicate or empty options) and exact duplicates (Oak repeats many starter questions across lessons and key stages; the first copy is kept).

## Credit line (show in the app)

> A [Subject] lesson by Oak National Academy licensed under Open Government Licence (OGL). https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

Each row carries `licence`, `licenceUrl` and `attribution` with the subject filled in (e.g. "A History lesson by Oak National Academy licensed under Open Government Licence (OGL)."). Oak's API terms also ask you not to sub-license the API itself, not to expose the API key or direct API calls in a public web service, and to respect any third-party asset licences (none are included here).
