# Real Estate Exam Prep

A study site for retaking the Iowa real estate license exam. It's built from two sources:

- **My study guide** (679 pages, 30 units): the study material. Every card and summary is quoted from the guide with its page number.
- **The Exam Prep book** (Iowa Association of REALTORS®): every practice question on the site. All 535 are copied word for word, with the book's answer key and page numbers. The site has no other questions.

## What's in it
- **Learn**: each unit's Key Point Review, the guide's "In Practice" tips, and the full section text
- **Drill**: flashcards for key terms, review lists, and fill-in-the-blank numbers
- **Test** (in each unit): 10 exam questions from the book section that covers the unit. Units with no matching book section (1, 5, 17, 23) have no test.
- **Tests**: four graded tests that together use every question: the **Iowa test** (all 70 Iowa License Law questions) and three National tests that split the 465 national questions: **National test 1** (Agency, Contracts, Federal Laws: 175), **National test 2** (Financing, Valuation, Math: 155) and **National test 3** (Property Ownership, Land Use: 135). They work like the practice questions: one question per page, and you see right away whether you got it right, with the correct answer and an explanation. Your place saves as you go. At the end you get your score. The results list every question you missed, with the right answer, a quote from the study guide and a link to that section of your notes.
- **Explanations**: 382 of the 509 non-math questions are matched by hand to the study-guide passage that covers them. The quote and section link appear on test results and when practicing. The other 127 say plainly that the guide doesn't cover them directly and link the related units. The 26 math questions show the work.
- **Weak spots**, **Numbers to know**, **Search** (the guide and every exam question)

## Answer key notes
The book's printed answer key is misnumbered in two places. The site corrects both and shows an **Answer note** on each affected question.
- **Math, Miscellaneous Questions**: the key has 15 answers for 14 questions. From question 3 on, the right answer is one line down in the key. The arithmetic confirms this, and each math question shows its work.
- **Property Ownership, Miscellaneous Questions 44–53**: the key skips 48 and its labels don't line up. Questions 48–52 use the answer one line down. For 44, 45, 46 and 53, the answer comes from the study guide, and the note gives the guide page.

Two other notes:
- **Valuation, Miscellaneous #27**: the key says A (averaging), but the study guide says reconciliation is not averaging (Guide p. 418). The site uses D.
- **Contracts, Miscellaneous #33**: the key's answer looks wrong, but the study guide doesn't cover the term, so the site keeps the book's answer and flags it.

## Profiles and saving
- Each person who uses the site makes a profile, and their progress is kept separately.
- Progress saves automatically in the browser.
- **Download backup file** saves your progress to a file. **Restore from backup file** loads it back on any computer or browser.
- **Reset exam prep** erases your profile's progress, and only works after you type `confirm`.

## Running it
It's a static site (`index.html` + `data.json` + `questions.json`) served by GitHub Pages. No build step and no server.

## Question wording

Every question and answer choice was proofread against the scanned book pages, so the wording matches the book word for word, including the book's own typos and punctuation. Two style differences only: answer letters are always capital A–E, and quotes are plain straight quotes.
