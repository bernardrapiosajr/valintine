# 💖 Interactive Valentine Card (Mobile Optimized)

A fun, interactive Valentine's card for mobile and web. It features a "No" button that smoothly slides away only when the user tries to click it.

## 🚀 Live Link
[👉 Click here to view my Valentine Card](https://bernardrapiosajr.github.io/valentine/)

## ✨ Key Features
* **Smooth Slide Trap:** Unlike other versions, the "No" button doesn't jump instantly. It uses a smooth CSS transition to slide away when tapped.
* **Click-Triggered Only:** The button stays still until it is actually clicked/tapped, making it feel like a real trap.
* **Romantic Music:** Background music starts automatically as soon as "Yes" is clicked.
* **Mobile Ready:** Uses `window.onload` logic to ensure the button doesn't fly off-screen on different phone sizes.

## 🛠️ How it was fixed for Phone
If you are building this, here are the fixes I used for mobile:
1.  **Initial Position Lock:** Used `getBoundingClientRect()` on load to prevent the button from "teleporting."
2.  **Cubic-Bezier Timing:** Added a bouncy slide effect for a more "alive" feel.
3.  **Touch Handling:** Optimized for mobile tapping by removing hover triggers.

## 👤 Credits
Created by **Bernard**
