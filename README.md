# SpanishWise v1.9.3

Learning Experience Pack.

## What changed

Content is preserved from v1.8:

- 1676 advanced C1/C2 words and expressions
- 95 grammar / usage topics
- 448 quiz questions

New learning features:

- Saved / favourite words
- Weak words review mode
- Wrong quiz answers automatically added to weak words
- Better search across word, meaning, definition, examples, chunks and related terms
- Category filter
- Level filter
- Quiz mode selector: all / weak / saved
- Daily streak counter
- Study stats and quiz accuracy
- Hide/reveal examples for active recall
- Settings page
- Cleaner responsive/mobile layout
- Cache updated to v1.9

## Upload

Upload all files to the repo root:

- index.html
- style-v1-9.css
- app-v1-9.js
- style.css
- app.js
- README.md
- icon.svg
- manifest.json
- service-worker.js

Then commit and hard refresh once.


## v1.9.1 fix

- Fixed search controls with delegated event handling
- Fixed category and level filter clearing
- Fixed Clear button reliability
- Added explicit button types to prevent accidental form-style behaviour
- Updated cache to v1.9.1


## v1.9.2 fix

- Fixed quiz category filtering
- Fixed quiz level filtering
- Changing quiz filters now rebuilds the actual question pool
- Changing quiz filters now generates a fresh question from the selected pool
- Saved and Weak quiz modes now respect category and level filters
- Updated cache to v1.9.2


## v1.9.3 mobile calm fix

- Removed the stats strip from Today, Words, Grammar, Quiz, Weak and Saved pages
- Kept full stats inside the Stats page
- Home page now focuses on the daily word instead of study metrics
- Daily word selection now uses a local calendar date key and changes once per local day
- Added the current date to the Today page so the daily-word behaviour feels intentional
- Updated cache to v1.9.3
