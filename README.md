# Neon Glowing Analog Clock 🕒

A stylish, minimalist analog clock built from scratch using HTML, CSS, and vanilla JavaScript. It features custom CSS variables for smooth layouts, a vibrant neon glowing backdrop animation, and real-time JavaScript rotation logic for the hands.

---

## 🚀 Features

* **Real-time Tracking:** Pulls the local system time and updates every single second using JS math calculations.
* **Neon Glow Aesthetics:** Uses dynamic CSS box-shadows, animations, and vibrant hand colors (Red for Hours, Green for Minutes, White for Seconds).
* **Responsive Layout:** Flexbox-centered container that automatically adjusts to viewport sizing.
* **Modern CSS Techniques:** Utilizes inline CSS variables (`--i`, `--clr`, `--h`) to efficiently position clock numbers and style the hands with minimal repetitive code.

---

## 🛠️ Tech Stack Used

* **HTML5:** Structures the clock face, numbers, and hands.
* **CSS3:** Handles the dark mode background, animations, and glowing aesthetics.
* **JavaScript (ES6):** Handles the time polling logic via `setInterval` and applies the dynamic 360-degree rotation angles.

---

## 📂 Project Structure

```text
├── index.html     # Main HTML file containing the layout
├── clock.css      # Styling, glow animations, and structural design
└── clock.js       # Core rotation and time-tracking logic
