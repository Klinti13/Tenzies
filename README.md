# 🎲 Tenzies Game

A fun and classic game built with **React** and **Vite**.

[**👉 Play the Game Live Here**](https://klinti13.github.io/Tenzies/)

## 📖 How to Play
The goal is to get all ten dice to show the same number.

1.  **Roll:** Click the "Roll" button to spin the dice.
2.  **Freeze:** Click on the dice you want to keep (freeze) at their current value.
3.  **Repeat:** Keep rolling the remaining dice until all of them match.
4.  **Win:** When all dice are the same, the game ends and you get a Confetti celebration! 🎉

## 🚀 Features
* **State Management:** Utilizes `useState` to track dice values and game status.
* **Side Effects:** Uses `useEffect` to check for winning conditions (all dice held + same value).
* **Accessibility:** Implements automatic focus on the "New Game" button using `useRef` for better keyboard navigation.
* **Confetti:** Visual celebration effect when the player wins.
* **Responsive:** optimized for both desktop and mobile devices.

## 🛠️ Tech Stack
* React.js (Hooks: `useState`, `useEffect`, `useRef`)
* Vite (for fast development and building)
* CSS3 (custom styling)
* JavaScript (ES6+)
* React Confetti Library

## 💻 How to Run Locally

If you want to clone and run this project on your computer:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Klinti13/Tenzies.git](https://github.com/Klinti13/Tenzies.git)
    ```

2.  **Navigate to the project folder:**
    ```bash
    cd Tenzies
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Start the local server:**
    ```bash
    npm run dev
    ```

---
*Created by [Klinti13](https://github.com/Klinti13)*
