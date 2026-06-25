# 🏆 Top-Maker (Binary Comparison Ranking Tool)

A lightweight, elegant, and highly efficient web application designed to help users rank and sort any list of items through intuitive, head-to-head binary choices.

**The concept is mine; the code was brought to life with the help of AI.**

---

## 💡 The Problem & The Solution

Have you ever tried to rank your favorite movies, books, project ideas, or team tasks, only to find yourself overwhelmed trying to manage a list of 10+ items at once? Humans are naturally terrible at absolute ranking but exceptionally good at making simple, binary choices (e.g., *"Is Option A better than Option B?"*).

This tool solves that exact problem. Instead of forcing you to mentally sort a massive list, it breaks the decision-making process down into rapid-fire, 1-on-1 matchups.

---

## ⚙️ How It Works (Under the Hood)

To minimize the number of decisions you have to make, the application utilizes a **Binary Insertion Sort algorithm**:

1. **Shuffle:** When you hit "Match Top", the app shuffles your items using the *Fisher-Yates* algorithm to remove any initial bias.
2. **Binary Search Placement:** As you pick your preference between two items, the algorithm uses binary search logic to find the exact ranking position for the next item in $O(\log n)$ comparison steps.
3. **The Result:** You get a beautifully ordered leaderboard from #1 to the bottom, calculated using the absolute minimum number of clicks required.

---

## ✨ Features

* 🚀 **Zero Dependencies:** Pure HTML5, CSS3, and Vanilla JavaScript. Single-file architecture.
* 🧠 **Smart Sorting:** Uses binary insertion logic so you don't waste time repeating redundant comparisons.
* 📱 **Immersive UI:** Clean fullscreen overlay mode for decision-making to help you focus on the choices.
* 📊 **Progress Tracking:** Live progress bar showing exactly how far along you are in finalizing your ranking.
* 🇺🇦 **Localized UI:** Fully written in Ukrainian for native clarity.

---

## 🛠️ Quick Start

Because this app is self-contained in a single file, launching it is incredibly straightforward:

1. Clone or download the repository.
2. Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Type in your elements, hit **"Зіставити Топ 🏆"**, and make your choices!

---

## 📝 Future Roadmap / Ideas

* Add export options (copy results as Markdown, text, or JSON).
* Dark mode support.
* Support for images/links as list elements.

---

## 📄 License

This project is open-source and free to use. Do whatever you want with it! Feel free to modify, extend, or share.
