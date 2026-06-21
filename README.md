# world-cup-tracker
48 teams. 104 matches. One HTML file. Zero database required!


# 🏆 FIFA World Cup 2026 Live Bracket Tracker

A lightweight, zero-dependency web application designed to track the official 48-team tournament format (Groups A through L) directly from your browser. 

No sign-ups, no databases, and no tracking cookies—just pure football analytics.

---

## ✨ Features

* **Complete 48-Team Format:** Pre-loaded with the official 12-group setup
* **Live Standings Engine:** Group tables dynamically calculate Points, Goal Difference (GD), and Goals For (GF) in real-time as you enter match scores.
* **Smart Knockout Tree:** Dynamically routes group winners, runners-up, and selected 3rd-place wildcards directly into the Round of 32 all the way to the Final.
* **Persistent Auto-Save:** Powered by local browser storage. Accidentally close your tab? Your bracket progress stays exactly where you left it.
* **Zero Configuration:** Single-file HTML design means it loads instantly and works flawlessly on both desktop and mobile layouts.

---

## 🚀 How to Run It

Since this app is built purely using static HTML, CSS, and vanilla JavaScript, there is nothing to install!

### 1. View It Live Online
Simply visit the GitHub Pages link generated for this repository:
`https://renegade-8086.github.io/world-cup-tracker/`

### 2. Run Locally
1. Download or clone this repository.
2. Double-click the `index.html` file to open it in any modern web browser.

---

## 🛠️ Built With

* **HTML5** - Semantic layout structure.
* **CSS3** - Responsive grid and flexbox bracket architecture.
* **JavaScript (ES6+)** - Reactive client-side calculations and data management.

---

## 🔄 Resetting Data
If your predictions go completely off the rails or you want to start a brand new simulation, simply click the **🔄 Reset Tournament** button in the header to safely wipe the cache and refresh the bracket.

## 📊 How to Sync Current Tournament Scores

Don't want to manually type in the scores for matches that have already been played? You can instantly sync your bracket with real-world results up to today!

### If you are using the Live Website Link:
1. Open the live tracker app link in your browser.
2. In the top header, click the blue **📥 Get Today's Scores** button. This will instantly download the official data file (`current_scores.json`) to your device.
3. Click the green **📤 Import Data File** button right next to it.
4. Select the `current_scores.json` file you just downloaded.

### If you are running the project locally (Offline/Desktop):
1. Make sure you have downloaded both `index.html` and `current_scores.json` into the exact same folder on your computer.
2. Open `index.html` to launch the app.
3. Click the blue **📥 Get Today's Scores** button.
4. When the app detects you are running locally, it will display a pop-up prompt. Click **OK**.
5. Select the `current_scores.json` file sitting inside your local folder.

*Boom! Your tournament tracker will instantly calculate the current standings and automatically unlock the correct knockout matchups based on real-world results.*
