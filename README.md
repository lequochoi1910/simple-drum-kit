# 🥁 Virtual Drum Kit

A fun, interactive web-based drum kit built with **Vanilla JavaScript**. This project simulates a real drum set, allowing users to play sounds using their computer keyboard.

![Project Screenshot](./screenshot.png)

## 🛠 Technologies Used
*   **HTML5:** Structured the layout and mapped keyboard keys to drum elements.
*   **CSS3:** Styled the interface, added background images, and created key press animation effects (transform/transition).
*   **Vanilla JavaScript (ES6):** Handled logic for keydown events, audio playback, and DOM manipulation.

## ✨ Key Features
*   **Keyboard Interaction:** Play sounds by pressing specific keys:
    *   `A`: Clap
    *   `S`: Hi-Hat
    *   `D`: Kick
    *   `F`: Open-Hat
    *   `G`: Boom
    *   `H`: Ride
    *   `J`: Snare
    *   `K`: Tom
    *   `L`: Tink
*   **Visual Feedback:** Keys light up and scale slightly when pressed to mimic interaction.
*   **Instant Audio:** Uses HTML5 `<audio>` tags for zero-latency sound playback.

## 📚 What I Learned
As a Software Engineering student specializing in Java, this project helped me sharpen my frontend skills:
1.  **DOM Events:** Deepened understanding of `window.addEventListener('keydown', ...)` to capture user input.
2.  **Audio Handling:** Learned how to rewind audio (`audio.currentTime = 0`) to allow rapid repetitive play.
3.  **CSS & JS Integration:** Practiced adding and removing CSS classes (`classList.add`, `transitionend`) dynamically to create smooth animations without complex libraries.

---
Made with ❤️ by [VIET NAM]
