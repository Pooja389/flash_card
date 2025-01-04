# Flash Card App

A simple and interactive flash card application built using Python's Tkinter library. This app helps you learn French vocabulary by showing French words on flashcards and flipping them to reveal their English translations. You can mark words you already know, and the app will update your vocabulary list accordingly.

---

## Features

- **Flashcards**: Display French words on one side and their English translations on the other.
- **Interactive Buttons**:
  - ✅ *Known Button*: Removes the current word from the learning list.
  - ❌ *Unknown Button*: Skips to the next word.
- **Data Persistence**: Updates and saves the vocabulary list (`french_words.csv`) by removing words you already know.
- **Auto-Flip**: Automatically flips the card to show the English translation after 3 seconds.

---

## Prerequisites

- **Python 3.x**
- Libraries:
  - `pandas`
  - `tkinter` (standard library)

---

## How to Run

1. Clone the repository
   ```bash
   https://github.com/Pooja389/flash_card.git
   ```
3. Make sure all required files (`card_front.png`, `card_back.png`, `right.png`, `wrong.png`, and `french_words.csv`) are in the same 
   folder as `flash.py`.
4. Open a terminal/command prompt, navigate to the folder, and run the script:
   ```bash
   cd flash-card
   ```
   ```bash
   python flash.py
   ```
---
## License
This project is free to use for educational purposes.


