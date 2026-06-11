# Project Structure

```
fiacs/
├── index.html              # Main business page
├── kids.html               # Adventure Quest kids app
├── style.css               # Global styles (main site)
├── CNAME                   # Custom domain config
├── README.md               # Repo readme
├── images/                 # (empty - available for future use)
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
- All pages at root level
- Images in `images/` directory
- One CSS file per site section (main site uses `style.css`, kids page is self-contained)
- New pages: add at root as `<name>.html`
