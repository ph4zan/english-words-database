# English Words Database

JSON database containing English words with translations, parts of speech, and linguistic information.

## Usage
\\\javascript
fetch('https://raw.githubusercontent.com/ph4zan/english-words-database/master/database.json')
    .then(response => response.json())
    .then(data => console.log(data))
\\\

## Files
- \database.json\ - Main database file
- \.gitignore\ - Git ignore rules

## Data Format
Each entry contains:
- \word\: English word
- \lemma\: Base form
- \pos\: Part of speech
- \	ranslation\: Russian translation
- \	ranscription\: Phonetic transcription
