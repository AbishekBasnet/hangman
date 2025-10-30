# This app is made with the help of copilot 
# Hangman Game (Flutter)

A fun and interactive **Hangman Game** built entirely with **Flutter** and **Dart**.  
It allows players to guess letters or the full word, with modern UI elements, animations, and responsive design — all built **without external state management libraries**.

---

##  Features

-  **Classic Hangman gameplay** with a modern UI  
-  Two play modes:  
  - **Letter Mode** – guess one letter at a time  
  - **Word Mode** – guess the entire word  
-  Tracks **correct**, **wrong**, and **used letters/words**  
-  Auto-selects **a new random word** every game  
-  On-screen **virtual keyboard** for easy letter guessing  
-  **Limit of 6 wrong guesses** before losing  
-  Victory and Game Over dialogs  
-  “Play Again” or “New Game” options  
-  Clean, responsive UI using **Material Design**

---

##  Tech Stack

| Technology | Purpose |
|-------------|----------|
| **Flutter (Dart)** | Cross-platform framework |
| **Material Design** | UI components & theming |
| **Random()** | Random word selection |
| **Set / List collections** | Game state management |

---

## Gameplay Overview

- The player tries to guess a randomly selected word.  
- You can **switch modes** between guessing **letters** or **whole words**.  
- Each incorrect guess adds to your **wrong guesses counter** (max 6).  
- Correct letters reveal themselves in the word display.  
- If all letters are revealed → **You Win!** 🥳  
- If wrong guesses reach 6 → **You Lose!** 😞  

---

##  UI Highlights

| Section | Description |
|----------|-------------|
| 🧠 **Word Display** | Shows correctly guessed letters and underscores for unknowns |
| 🔤 **Virtual Keyboard** | Interactive buttons for each letter (Q–M) |
| 💬 **Mode Toggle** | Switch between “Letters” and “Word” modes |
| 🧾 **Guessed Letters Summary** | Displays correct and wrong letters |
| ⏱️ **Game Status Dialogs** | Alerts for Win/Loss with replay option |

---

## 🗂️ Folder Structure

