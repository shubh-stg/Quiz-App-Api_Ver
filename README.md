# Quiz App - Basic Version 🎯

A simple and interactive **Quiz Application** built using **React** that fetches multiple-choice questions from the **Open Trivia DB API**. This version focuses on core quiz functionality like question rendering, option selection, and score tracking — without additional features like spinners, timers, or form-based filters.

---

## ✅ Features

- 🎮 10 randomly fetched questions from Open Trivia DB
- 💡 Multiple choice options (1 correct + 3 incorrect)
- 🧠 Instant answer validation (highlight correct/wrong)
- 📊 Score tracking and result display
- 🔁 Reset and Retake functionality

---

## 🛠️ Tech Stack

- **React** (with Hooks)
- **JavaScript (ES6+)**
- **CSS Modules** for styling
- **OpenTDB API** for fetching quiz data

---

## 🔧 How It Works

- On app load, the quiz fetches 10 multiple-choice questions using the OpenTDB API.
- Each question has 4 options — one correct and three incorrect.
- Clicking an option locks the answer and highlights the correct one.
- User proceeds with "Next" to move through the quiz.
- Final score is shown at the end with an option to reset or replay.

---
## Open Trivia Api
https://opentdb.com/api_config.php
