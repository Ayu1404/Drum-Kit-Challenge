# **Drum Kit Challenge**

A fun and interactive web application that allows users to create drum sounds using their keyboard or by clicking on-screen buttons. Each button and key is mapped to a different drum sound, providing an engaging musical experience.

---

## **Features**
- **Interactive Drum Set**:
  - Play drum sounds by either clicking the buttons or pressing the corresponding keys (`w, a, s, d, j, k, l`).
- **Dynamic Visual Feedback**:
  - Buttons briefly change appearance when clicked or activated by a keypress to enhance the user experience.
- **Variety of Sounds**:
  - Each key is mapped to a unique sound (e.g., tom-toms, crash cymbal, kick drum, and snare).
- **Keyboard and Mouse Support**:
  - Compatible with both keyboard inputs and mouse clicks for versatile interaction.

---

## **Technologies Used**
- **HTML5**: Structures the content and layout of the drum kit interface.
- **CSS3**:
  - Enhances the visual design of the buttons and overall layout.
  - Includes animations for button clicks.
- **JavaScript**:
  - Implements the core logic for sound playback and interaction handling.
  - Detects keyboard events and mouse clicks to trigger sounds dynamically.

---

## **Getting Started**

### **Prerequisites**
- A modern web browser with support for JavaScript and audio playback.

---

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/Ayu1404/Drum-Kit-Challenge.git
   cd Drum-Kit-Challenge
   ```

2. Open the **index.html** file in your browser to start playing:
   ```bash
   open index.html
   ```

---

## **How to Play**
1. **Play with Buttons**:
   - Click on any of the on-screen drum buttons (`w, a, s, d, j, k, l`) to hear its associated sound.
2. **Play with Keys**:
   - Press the corresponding keyboard keys to trigger the same sounds.
3. **Visual Feedback**:
   - Watch the buttons light up when clicked or when their respective keys are pressed.

---

## **Sound Mapping**
| Key/Button | Sound             | File Name        |
|------------|--------------------|------------------|
| **w**      | Tom 1             | `tom-1.mp3`      |
| **a**      | Tom 2             | `tom-2.mp3`      |
| **s**      | Tom 3             | `tom-3.mp3`      |
| **d**      | Tom 4             | `tom-4.mp3`      |
| **j**      | Crash Cymbal      | `crash.mp3`      |
| **k**      | Kick Drum         | `kick-bass.mp3`  |
| **l**      | Snare Drum        | `snare.mp3`      |

---

## **How It Works**
1. **Event Listeners**:
   - `click` event is added to each button to detect mouse clicks.
   - `keypress` event is used to listen for key presses.
2. **Sound Playback**:
   - Depending on the key/button pressed, a corresponding sound file is played using the `Audio` object in JavaScript.
3. **Button Animation**:
   - Buttons briefly animate (e.g., a “pressed” appearance) when activated by a click or key press.
   - The animation effect is removed after 100 milliseconds using `setTimeout`.

---

## **Project Structure**
### **index.html**:
- Contains the structure of the drum kit, including buttons representing each drum sound.
- Includes references to the CSS and JavaScript files for styling and interactivity.

### **index.js**:
- Implements the main logic:
  - Detects keyboard and mouse inputs.
  - Maps inputs to sounds using a `switch` statement.
  - Plays the appropriate audio file.
  - Handles button animations.

### **styles.css**:
- Defines the visual layout and styling of the drum kit.
- Adds animations for button feedback.

---

## **Contributing**
Contributions are welcome! To contribute:
1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## **License**
This project is licensed under the MIT License, allowing you to modify and distribute the project with proper attribution.

---

## **Acknowledgments**
- Inspired by the love of music and creativity.
- Special thanks to online resources for drum sound effects used in this project.
