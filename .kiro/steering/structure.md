# Project Structure

```
fiacs/
├── index.html              # Main business page
├── style.css               # Global styles (main site)
├── CNAME                   # Custom domain config
├── README.md               # Repo readme
├── images/                 # (empty - available for future use)
├── kids/                   # Adventure Quest kids app
│   ├── index.html          # Main kids page (Adventure Quest)
│   ├── counting.html       # Counting practice
│   ├── learning.html       # Learning hub
│   ├── kindness.html       # Be Kind tracker
│   └── maths.html          # Maths practice
├── games/                  # Games section
│   ├── index.html          # Games hub
│   ├── stats.html          # Stats & achievements
│   ├── reaction.html       # Reaction speed game
│   ├── scramble.html       # Word scramble game
│   ├── mathrace.html       # Math race game
│   ├── pattern.html        # Pattern match game
│   ├── wordsearch.html     # Word search game
│   ├── quiz.html           # Quiz game
│   ├── memory.html         # Memory card game
│   ├── puzzle.html         # Sliding puzzle game
│   └── sudoku.html         # Sudoku game
├── sos/                    # SOS section
│   └── index.html          # SOS Police page
├── .github/
│   └── workflows/
│       └── static.yml      # GitHub Pages deploy workflow
└── .kiro/
    ├── steering/
    │   ├── product.md      # What this project is
    │   ├── tech.md         # Tech decisions
    │   └── structure.md    # This file
    └── prompts/            # Kiro CLI prompt files
```

## Conventions
- Pages grouped by section: `kids/`, `games/`, `sos/`
- Main entry page per section is `index.html` (e.g. `/kids/`, `/games/`, `/sos/`)
- Internal links use absolute paths (e.g. `href="/kids/"`, `href="/games/stats.html"`)
- Images in `images/` directory
- One CSS file for the main site (`style.css`); kids/games pages are self-contained with inline styles
- New pages: add to the appropriate section folder
