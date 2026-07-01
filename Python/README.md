# Digital Flashcards App - Python Version

This is the Python version of Digital Flashcards App.

It is a simple study tool for loading flashcards from CSV files. It does not save your questions or progress after the app is closed.

## Requirements

- Python 3
- PySide6

## Setup and run

### Linux / macOS

Open a terminal in this folder, then run:

```sh
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python flashcards.py
```

### Windows

Open Command Prompt in this folder, then run:

```bat
py -m venv .venv
.venv\Scripts\activate
python -m pip install -r requirements.txt
python flashcards.py
```

## CSV format

Use spreadsheet software and export as CSV.

A row with one question and one answer loads as a definition card:

```csv
question,answer
What is photosynthesis?,How plants use light to make energy
```

A row with one question, one correct answer, and wrong answers loads as a multiple choice card:

```csv
question,answer,wrong1,wrong2,wrong3
What planet is known as the Red Planet?,Mars,Venus,Jupiter,Saturn
```

You can use fewer than three wrong answers.

## Notice

No warranty is provided.
