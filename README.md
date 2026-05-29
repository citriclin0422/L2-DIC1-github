# L2-DIC1-github

Welcome to the project repository for **Citric Lin**. This repository contains a web-based interactive greeting dashboard and a simple Python Tkinter window script.

## Repository Contents

### 1. Interactive Greeting Dashboard (`index.html`)
A responsive, high-performance web dashboard displaying a personalized greeting and a live digital clock.

* **Features:**
  * **Real-time Digital Clock:** Displays the current hours, minutes, and seconds, updating in real time.
  * **Formatted Date Display:** Displays the current weekday, month, day, and year using the local language format.
  * **Theme Switcher:** Includes interactive theme options (Indigo, Emerald, Amber) that dynamic-shift background glow highlights, borders, and gradient accents.
  * **Modern Aesthetics:** Utilizes a custom dark theme, glassmorphic card containers, and blurred backdrop spheres.
  * **Responsive Design:** Optimized to render on screens of any size (mobile, tablet, and desktop).

* **How to run:**
  * Double-click `index.html` to open it directly in any modern web browser.
  * Alternatively, run a local development server in the root folder using Python:
    ```bash
    python -m http.server 8000
    ```
    Then visit `http://localhost:8000` in your browser.

---

### 2. Python GUI Exercise (`0527.py`)
A basic Python script utilizing the standard `tkinter` library.

* **Features:**
  * Imports `tkinter` module.
  * Initializes and displays a standard system GUI window (`Tk` object).
* **How to run:**
  * Ensure Python is installed, then run the script via terminal or cmd:
    ```bash
    python 0527.py
    ```

---

## Technical Details

* **Language/Frameworks:** HTML5, CSS3 (Vanilla CSS variables and layout), Javascript (ES6), Python 3.
* **Fonts:** Outfit (imported from Google Fonts).
* **Git Configurations:** Ignored the Python virtual environment folder (`aivm/`) using `.gitignore` to keep the repository lightweight and clean.
