# FIA Consultancy Services

IT consultancy website based in Belgium — [www.fiacs.be](https://www.fiacs.be)

## Sections

### Main Site (`/`)
Business page showcasing IT consultancy services — infrastructure, cloud, cybersecurity, and digital strategy.

### Kids — Adventure Quest (`/kids/`)
Gamification app for tracking good deeds and learning activities.

- **Adventure Quest** — Points tracker with levels, milestones, and team quests
- **Counting** — Counting practice
- **Learning** — Learning hub with links to educational activities
- **Be Kind** — Kindness tracker
- **Maths** — Maths practice

### Games (`/games/`)
Collection of browser-based games with XP progression, achievements, and stats tracking.

- **Reaction Speed** — Test your reflexes
- **Word Scramble** — Unscramble words
- **Math Race** — Solve problems against the clock
- **Pattern Match** — Find the sequence
- **Word Search** — Find hidden words
- **Quiz** — Knowledge quiz
- **Memory** — Card matching game
- **Puzzle** — Sliding tile puzzle
- **Sudoku** — Classic number puzzle
- **Stats & Achievements** — Level journey, streaks, high scores

### SOS (`/sos/`)
Emergency info page.

## Tech Stack

- Plain HTML5, CSS3, vanilla JavaScript
- No frameworks or build tools
- GitHub Pages with custom domain
- localStorage for game state persistence

## Project Structure

```
fiacs/
├── index.html          # Main business page
├── style.css           # Main site styles
├── kids/               # Adventure Quest section
├── games/              # Games section
├── sos/                # SOS section
└── .github/workflows/  # GitHub Pages deployment
```

## Deployment

Automatically deployed to GitHub Pages on push to `main` via GitHub Actions.
