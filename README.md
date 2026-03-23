# ERMonthlyIssues

## KAVACH ER Issues Dashboard — March 2026

Interactive dashboard for tracking **LS Mode**, **SR Mode**, and **Tag Missing** issues across the Eastern Railway KAVACH signalling system.

### 🔗 Live Dashboard
**[View Dashboard via GitHub Pages](https://viswanadhMalladi77.github.io/ERMonthlyIssues/)**

### 📊 Data Source
- **Google Sheet:** [March_LS_SR_issues](https://docs.google.com/spreadsheets/d/1VSETtuuIgVrDn3Hk2CSXaYAphGM2vrmBCC94UARWeSk/edit?usp=sharing)
- **Records:** 353 issues | **Period:** 01–21 March 2026
- **Stations:** 64 | **Locomotives:** 60

### 📈 Dashboard Features
| Feature | Description |
|---------|-------------|
| **4 Slicers** | Date, Station, Issue Type, Direction — cross-filter all charts |
| **Daily Trend** | Line chart of LS/SR/Tag issues over time |
| **Doughnut** | Proportional issue type distribution |
| **Sub-Category Bar** | Horizontal bar of Radio failures, SOM, KAVACH exit, etc. |
| **Polar Area** | Direction-wise analysis (DN/UP) |
| **Station Rankings** | Top 12 most affected stations |
| **Loco Rankings** | Top 12 most affected locomotives |
| **Stacked Bar** | Station × Issue Type composition |
| **Radar** | Multi-dimensional issue profile |
| **Heatmap** | Station × Date density grid |
| **Cumulative Line** | Running total through the month |
| **Bubble Chart** | Station × Loco intersection |
| **Data Table** | Scrollable filtered issue log |

### 🎨 Theme
Sea blue + beige with animated ocean waves, floating particles, and smooth chart transitions.

### 🛠️ Tech Stack
- **Chart.js 4.4** — all chart visualizations
- **Vanilla HTML/CSS/JS** — no build step required
- **Google Fonts** — DM Sans + Playfair Display

### 📂 Files
```
├── index.html          # Dashboard (self-contained, all data embedded)
├── ER_Internal_Sheet_Summary_of_Issues_-_March_LS_SR_issues.csv  # Raw data
└── README.md
```

---
*Eastern Railway · KAVACH Signalling · Internal Use*
