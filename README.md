# 🎀 Hello-Kitty-Themed-Calculator

> A super cute, scientific calculator inspired by Hello Kitty aesthetics! Built with pure HTML, CSS, and JavaScript. 

### 🔗 [Click here to use the Calculator!](https://sameeha0.github.io/Hello-Kitty-Themed-Calculator/)

![License](https://img.shields.io/badge/License-MIT-blue)
![GitHub stars](https://img.shields.io/github/stars/Sameeha0/Hello-Kitty-Themed-Calculator?style=social)

---

## Features

- **Scientific Mode**: Fully functional scientific calculator including Trigonometry (sin, cos, tan), Logarithms, Square Roots, Powers, and Pi (π). 
- **Natural Expression Input**: Write equations just like you see them in textbooks (e.g., `sin(30) + √25`).
- **Implicit Multiplication**: Smartly understands that `2sin(30)` means `2 × sin(30)`. 
- **Calculation History**: Slide-out sidebar with smooth mobile scrolling. Clear history and close (×) buttons work reliably. Click any history item to reuse the result. 
- **Kawaii Design**: Pastel pink/white palette, rounded shapes, and soft shadows.
- **Cute Animations**: Floating hearts background, bouncy buttons, and a wiggling bow! 🎀
- **Dark Mode**: Switch between **Classic Pink** and **Dark Chic** modes. Display text colors adapt (dark pink in light theme, light pink in dark theme). 
- **Cat Face UI**: Adorable minimal cat face with ears and whiskers. 🐱
- **Responsive & Scroll-Friendly**: Desktop buttons sit fully visible above the calculator; on mobile, controls stay visible and avoid overlap while you scroll. 
- **Error Handling**: Concise "Error" message with smaller font for invalid equations (e.g., `0/0`).
- **Keyboard Support**: Type numbers and operations directly from your keyboard. 

## Tech Stack

- **HTML5**: Semantic structure with separate sections for Display, History, and Controls.
- **CSS3**: Custom properties (variables), Grid/Flexbox layouts, keyframe animations, and media queries for mobile responsiveness.
- **JavaScript (ES6+)**: 
    - Advanced expression parsing (Infix notation).
    - LocalStorage for persisting history.
    - Event delegation and DOM manipulation.
- **Fonts**: Google Fonts (Baloo 2 & Quicksand).

## How to Run Locally

1.  **Clone the repository** (or download the files):
    ```bash
    git clone https://github.com/your-username/hello-kitty-calculator.git
    ```
2.  **Navigate to the folder**:
    ```bash
    cd hello-kitty-calculator
    ```
3.  **Open `index.html`**:
    - You can simply double-click `index.html` to open it in your browser.
    - OR use a local server (like Live Server in VS Code) for the best experience.

## Folder Structure

```
/hello-kitty-calculator
│
├── index.html      # Main HTML structure (Calculator & UI)
├── style.css       # All styling, animations, and themes
├── script.js       # Calculator logic, history management, and math functions
└── README.md       # Project documentation (You are here!)
```

## Themes

| Pink Theme (Default)  | Dark Mode         |
|-----------------------|-------------------|
| Soft pinks & baby red | Dark pink & black |
| Classic Kawaii vibe   | Chic night vibe   |

## What's New

- Desktop top controls are placed directly above the calculator and fully visible.
- Mobile top controls move to the top-left and remain visible while scrolling, avoiding overlap with the history close (×) button.
- History sidebar supports touch-friendly scrolling; Clear History and Close buttons are wired and working.
- Display text color now matches theme: dark pink (light mode) and light pink (dark mode).
- Error message is shortened to "Error" and styled smaller to fit within the display area.

## Credits

Made with 💕 by **Sameeha**.

---
*Note: This project is a fan creation inspired by Hello Kitty aesthetics and does not use copyrighted assets.*
