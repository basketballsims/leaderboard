# Summer Squad Leaderboard 🏀

**Burlington Force Basketball — Summer Training Tracker**

A mobile-first Progressive Web App for the Burlington Force youth basketball squad to track summer workout sessions, shot volumes, and compete on a live leaderboard.

## Features

- **Personalized login** — players pick their name once; the app remembers them on their device
- **Live points scoreboard** — see your session points update in real-time as you log shots
- **Shot tracking** — Short (layups/inside charge circle), Mid (charge circle → free throw line), Long (beyond free throw line)
- **Game sessions** — 1v1, 3v3, 5v5 session tracking (30 min each)
- **Persistent leaderboard** — all sessions saved to shared backend; everyone sees the same live standings
- **Daily motivational quote** — fresh AI-generated quote every morning to energize the squad
- **Top 5 Prize Banner** — tracks the prize positions updated in real time
- **Season ranks** — Legend (500+ pts), Bucket Getter (300–499), Grinder (150–299), Getting Started

## Scoring Matrix

| Shot Type | Zone | Points |
|-----------|------|--------|
| Short | Inside charge circle & layups | 10 pts per 100 made |
| Mid | Charge circle → free throw line | 20 pts per 100 made |
| Long | Beyond free throw line | 75 pts per 100 made |

| Game Format | Points |
|-------------|--------|
| 1v1 session (30 min) | 5 pts |
| 3v3 session (30 min) | 8 pts |
| 5v5 session (30 min) | 12 pts |

## Squad Roster

#0 Alex Maalouf · #1 Cameron Rasheed · #2 Ian McGaw · #3 Nixon Lovisa · #7 Jonah Quintana · #12 Justin Joe · #13 Ben Allen · #14 David Messim · #23 Nate Dagg · #25 Andrei Calin · #33 Tommy Arboleda · #77 Cohen Sims · #93 Nathan Fox

## How to Add to Home Screen

**iPhone (Safari):**
1. Open the app link in Safari
2. Tap the Share button (box with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add" — done!

**Android (Chrome):**
1. Open the app link in Chrome
2. Tap the three-dot menu
3. Tap "Add to Home screen"
4. Tap "Add"

## Tech

- Vanilla HTML/CSS/JS — no framework, no install needed
- `localStorage` for player identity (per device)
- Shared persistent storage for leaderboard data
- Anthropic API for daily motivational quotes
- Fully mobile-optimized, works offline after first load

## Season

June · July · August — Top 5 players win prizes at end of season (early August)

---

*Built for Burlington Force Basketball by Sims Consulting Inc*
