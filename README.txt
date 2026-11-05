GK MOCK TEST - UPDATED PROJECT

Upload the contents of this folder to the root of your existing Vercel/GitHub project, keeping folders as shown.

Question banks:
- js/exams/gk-sets.js: 10 existing GK sets
- js/exams/bihar-police.js: 4 existing Bihar Police mocks
- js/exams/bpsc-prelims.js: existing BPSC mocks plus 12 new practice sets (350 questions from the supplied question PDFs; eleven 30-question sets and one 20-question final set)
- js/data.js: combines banks for the existing app

Modes:
- Practice Mode: instant correct/wrong feedback (existing behaviour)
- Exam Mode: no answer reveal while attempting; change answers, mark for review, submit, then review all answers

Question schema: {t: topicIndex, e: English question, h: Hindi question, o: [[English,Hindi] x 4], a: correct option index, x: optional explanation}

Existing feedback/footer files are retained. The existing question sets are preserved; one existing GK set contains 73 questions, so its actual count is shown dynamically.

BPSC: the two existing BPSC mock tests are preserved. Twelve new BPSC practice sets are appended. The supplied Important Notes Set-3 PDF is revision material, not an MCQ question paper, so it was not converted into questions.
