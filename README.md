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

No installation, no build step, no dependencies — it's a single HTML file.

### 1. View It Live Online
Visit the GitHub Pages link for this repository:
`https://renegade-8086.github.io/world-cup-tracker/`

### 2. Run Locally
1. Download `index.html` from this repository.
2. Double-click it to open in any modern web browser (Chrome, Edge, Firefox, Safari).

---

## 🗂️ The Three Tabs

| Tab | What it does |
|---|---|
| **Group Standings** | Live table for all 12 groups — P, W, D, L, GF, GA, GD, Pts. Auto-sorts by Pts → GD → GF as you enter scores. |
| **Group Fixtures** | Match-by-match score entry for all 72 group stage games. Default view shows today's matches at the top, descending to Matchday 1. Toggle *"Show all fixtures including future"* to see the full schedule in chronological order. |
| **Knockout Bracket** | Horizontal column view from Round of 32 through to the Final and 3rd-place play-off. Placeholder slots (1A, 2B, W73, etc.) automatically resolve to real team names as group scores are entered. Entering a knockout score with a clear winner instantly propagates that team into the next round. |

---

## 📊 Syncing Today's Scores

To load real-world results without typing every score manually:

1. Click **Get Today's Scores** (sky blue button in the header).
   This downloads the latest `current_scores.json` from this repository to your device.
2. Click **Import Data** (green button, right next to it).
3. Select the `current_scores.json` file you just downloaded.

Group standings, fixtures, and the knockout bracket all update instantly.

---

## 🛠️ Header Buttons at a Glance

| Button | Colour | Action |
|---|---|---|
| **Reset Scores** | Red | Clears every entered score — prompts for confirmation first. |
| **Get Today's Scores** | Sky blue | Downloads `current_scores.json` from the repo (latest official results). |
| **Import Data** | Green | Load a previously exported or downloaded JSON file into the tracker. |
| **Export Scores** | Blue | Saves your current score state as `worldcup2026_scores.json` to your device. |

---

## 🛠️ Built With

* **HTML5 / CSS3 / Vanilla JavaScript (ES6+)** — no frameworks, no build tools.
* **Tailwind CSS** (CDN) — utility-first styling.
* **Font Awesome** (CDN) — icons.

---

## 🔄 Keeping Scores Up To Date

`current_scores.json` in this repository is updated as matches are played. Use the **Get Today's Scores → Import Data** flow above whenever you want to pull in the latest results.
