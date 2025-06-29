# nhl-playoff-elimination-tracker

# NHL Playoff Elimination Tracker 🏒

An interactive visualization tool that maps team eliminations during the Stanley Cup Playoffs. Designed to provide fans and analysts with a dynamic way to track playoff progression over time, across multiple seasons.

![screenshot placeholder](#)

---

## 🔧 Features

- 📅 **Season Selector**: Switch between 2022, 2023, 2024, and 2025
- 🗺️ **North American Team Map**: Shows all 32 teams using custom logos
- ❌ **Elimination Animation**: Logos fade or shrink based on playoff exit date
- 🔁 **Dynamic Updates**: Data changes based on selected season
- 🎛️ **Toggle Controls (Coming Soon)**: Play/pause animations, logo vs. text mode

---

## 🗂️ Project Structure

```bash
.
├── index.html                  # Main interactive page
├── scripts/
│   └── app.js                 # Season logic & elimination animations
├── data/
│   ├── elimination_dates_2022.csv
│   ├── elimination_dates_2023.csv
│   ├── elimination_dates_2024.csv
│   └── elimination_dates_2025.csv
├── logos/
│   ├── COL.png
│   ├── BOS.png
│   └── ...                   # One logo per team
└── README.md
