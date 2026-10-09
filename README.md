# 24-Week Lean Athletic Transformation Tracker

A personal, interactive fitness tracking website built for home training with body weight + backpack.

**Live site:** [https://YOUR-USERNAME.github.io/24-weeks/](https://YOUR-USERNAME.github.io/24-weeks/)

---

## What this is

A complete 6-month home workout tracker with:

- ✅ **Interactive daily training checkbooks** — Monday, Wednesday, Friday
- 📊 **24-week calendar** — tick sessions, log weight, nutrition score, observations
- 🏋️ **Exercise illustration images** for every training day
- ⭐ **Difficulty rating** per exercise (star system)
- 💾 **Auto-saves to your browser** (localStorage — no server, no account needed)
- 📈 **Progress bar** tracking sessions completed across 24 weeks

## Training Schedule

| Day | Focus | Exercises |
|---|---|---|
| **Monday** | Upper Body + Core | Push-ups, Backpack Rows, Pike Push-ups, Lateral Raises, Biceps Curls, Plank |
| **Wednesday** | Legs + Core | Bodyweight Squats, Split Squats, RDL, Glute Bridges, Calf Raises, Dead Bug |
| **Friday** | Full Body + Shoulders | Push-ups, One-Arm Rows, Pike Push-ups, Lateral Raises, Squats, RDL, Reverse Crunches, Plank |

## Equipment

- Body weight
- Backpack filled with books or water bottles (adjustable load)
- Chair or table (for rows)
- Water bottles (for lateral raises)

## Starting Profile

- Height: 183 cm (6 ft)
- Start Weight: 68 kg
- Start Waist: 88 cm
- Experience: Beginner
- Duration: 45–55 min per session

---

## Publish to GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder `/`
4. Site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

## File Structure

```
24-weeks/
├── index.html          ← Homepage
├── calendar.html       ← 24-week interactive calendar
├── days/
│   ├── monday.html     ← Monday training checkbook
│   ├── wednesday.html  ← Wednesday training checkbook
│   └── friday.html     ← Friday training checkbook
├── assets/
│   ├── css/
│   │   └── style.css   ← Shared stylesheet
│   └── images/
│       ├── hero.jpg    ← Hero banner
│       ├── monday.jpg  ← Monday exercise illustration
│       ├── wednesday.jpg ← Wednesday exercise illustration
│       └── friday.jpg  ← Friday exercise illustration
└── README.md
```

## Privacy

All session data is stored locally in your browser using `localStorage`. No data is sent to any server. Clearing browser storage will erase your logs — consider exporting important data periodically.

---

*Built for personal use · No gym needed · Home training*
