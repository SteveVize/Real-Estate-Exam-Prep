# Real Estate Exam Prep

A study site for retaking the Iowa real estate license exam. It's built from two sources:

- **My study guide** (679 pages, 30 units). Every card, recall question and summary is quoted from the guide with its page number.
- **The Exam Prep book** (Iowa Association of REALTORS®). All 535 practice questions are copied word for word, with the book's answer key and page numbers. These are the closest match to the wording of the real test, so the site uses them first.

## What's in it
- **Exam questions**: every question from the Exam Prep book, sorted into the book's sections: Iowa License Law, Federal Laws, Agency, Contracts, Financing, Valuation, Property Ownership, Land Use and Real Estate Math. Practice each Speed and Miscellaneous set in the book's order, practice 20 at a time (unseen first), or retry the ones you missed. Math answers show the work.
- **Learn**: each unit's Key Point Review, the guide's "In Practice" tips, and the full section text
- **Drill**: flashcards for key terms, review lists, and fill-in-the-blank numbers
- **Test**: 10 exam questions from the book section that covers the unit, with the guide recall test one click away
- **Mock exam**: 25, 50, 100 or a full 120 questions. With book questions, the full exam has 40 Iowa and 80 national questions, weighted like the content outline on page 4 of the book.
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
