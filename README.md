# 💖 Interactive Valentine Card (Mobile Optimized)

A fun, interactive Valentine's card for mobile and web. It features a "No" button that perfectly aligns with the "Yes" button initially, then dodges the user when they try to click it.

## 🚀 Live Link
[👉 Click here to view my Valentine Card](https://bernardrapiosajr.github.io/valentine/)

## ✨ Key Features
* **Perfect Inline Alignment:** Fixed the issue where buttons didn't stay on the same line on mobile devices.
* **The Dodge Trap:** The "No" button starts in the natural layout and switches to `fixed` positioning only when interacted with.
* **Valentine Message:** A sweet "Happy valentines!" message appears after clicking "Yes."
* **Mobile Ready:** Uses `touch-action: none` to prevent accidental zooming while trying to catch the button.

## 🛠️ How it was fixed for Phone
If you are building this, here are the mobile-specific fixes:
1. **Flexbox Layout:** Buttons are wrapped in a flex container without absolute positioning at the start to ensure they stay side-by-side on all screen widths.
2. **Fixed Switch:** Changed logic to trigger `position: fixed` only inside the JavaScript function. This prevents the button from "jumping" during the initial page load.
3. **Viewport Padding:** Added math to ensure the button never dodges off the edge of small phone screens.

## 👤 Credits
Created with ❤️ by **Bernard**
