# hepta-ws-timer
# ⏱️ HEPTA Workshop Timer

**HEPTA Workshop Timer** is a simple, stylish, browser-based timer tool designed for hands-on workshops, lectures, demonstrations, and satellite education activities.

It combines a **large countdown timer** with an optional **PDF slide viewer**, making it useful for workshop facilitation, presentation sessions, group activities, and time-managed exercises.

![Status](https://img.shields.io/badge/status-ready-brightgreen)
![Made with](https://img.shields.io/badge/made%20with-HTML%20%2F%20CSS%20%2F%20JavaScript-blue)
![Use case](https://img.shields.io/badge/use%20case-workshop%20timer-73d2ff)

---

## ✨ Features

### 🕒 Large Countdown Timer
- Big, easy-to-read countdown display
- Supports minutes and seconds
- Preset timer options from **30 seconds to 60 minutes**
- Quick time adjustment buttons: `-5 min`, `-1 min`, `+1 min`, `+5 min`

### 📄 PDF Show Mode
- Upload and display a PDF directly in the browser
- Recommended for showing slides converted from PowerPoint
- Timer stays visible beside the PDF for smooth workshop operation

### 🎯 Timer Only Mode
- Focused full-screen timer display
- Large centered numbers for visibility from a distance
- Ideal for group work, countdowns, breaks, and hands-on activities

### 🔔 Warning & Alarm
- Custom warning time setting
- Warning sound before time is up
- Repeating alarm when the timer reaches zero
- Dedicated **Stop Alarm** button

### 🧭 Clean Settings Panel
- All controls are gathered in the left-side settings panel
- Start, pause, resume, reset, display mode, fullscreen, and PDF upload are all in one place
- Panel can be hidden and reopened with the `☰` button

### 🌌 Visual Design
- Dark glassmorphism-style interface
- Gradient background
- Large progress bar
- Warning and time-up visual effects
- Presentation-friendly appearance

---

## 🚀 How to Use

1. Open `hepta_timer.html` in a web browser.
2. Set the session title.
3. Choose a preset time or enter your own minutes and seconds.
4. Set the warning time.
5. Upload a PDF if you want to use the slide display.
6. Choose either:
   - **PDF Show**
   - **Timer Only**
7. Press **Start**.
8. When the timer ends, press **Stop Alarm** to stop the sound.

---

## 🖥️ Display Modes

### PDF Show

Use this mode when you want to show slides and a timer together.

Recommended for:

- Workshop lectures
- Hands-on activity instructions
- Group exercises
- Demonstrations

### Timer Only

Use this mode when you want a clean, highly visible countdown timer.

Recommended for:

- Break time
- Discussion time
- Mission activity countdowns
- Presentation practice

---

## 📦 File Structure

```text
hepta_timer.html
README.md
```

This project is intentionally lightweight.  
No external libraries are required.

---

## 🛠️ Built With

- HTML
- CSS
- JavaScript
- Web Audio API

---

## 🎓 Intended Use

This timer was designed for HEPTA-SAT and hands-on satellite education workshops.

It is especially useful when participants need to understand time constraints during practical activities such as:

- Satellite system design exercises
- Mission planning
- Group discussions
- Hardware demonstrations
- Data analysis sessions
- Presentation preparation

---

## 💡 Recommended Workflow

For PowerPoint presentations:

```text
PowerPoint → Export as PDF → Upload PDF into HEPTA Workshop Timer
```

This allows the slides and timer to be displayed together in a single browser window.

---

## 🔊 Notes

- Browser audio may require the user to press **Start** before sounds can play.
- Fullscreen mode depends on browser permissions.
- PDF display uses the browser's built-in PDF viewer.

---

## 🌟 Concept

Workshops often need more than just a timer.

They need a tool that is:

- easy to operate,
- visible from the back of the room,
- suitable for presentations,
- not distracting,
- and visually polished.

**HEPTA Workshop Timer** was created to support smooth, time-managed, and engaging learning experiences.

---

## 📜 License

This project can be modified and used for educational and workshop purposes.

---

## 🙌 Author

Created for HEPTA-SAT style hands-on education and workshop facilitation.
