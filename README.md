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
`https://<your-username>.github.io/<your-repository-name>/`

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

## 📊 Current Tournament Scores (Up to Date!)

Want to skip manually typing in the scores of the matches that have already been played? 

1. 1. Click this link to download: <a href="https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/current_scores.txt" download="current_scores.json">Download Current Scores File</a>
2. Open the live tracker app link.
3. Click the **📤 Import Data** button in the header.
4. Select the `current_scores.json` file you just downloaded. 

*Boom! Your bracket will instantly sync up with all real-world scores up to today.*
