# Tech Stack

## Language & Framework
- Plain HTML5, CSS3, vanilla JavaScript
- No build tools, bundlers, or frameworks
- No dependencies

## Hosting & Deployment
- GitHub Pages (static deployment)
- Custom domain: www.fiacs.be (via CNAME)
- CI/CD: GitHub Actions (`.github/workflows/static.yml`) — deploys on push to `main`

## Storage
- localStorage for kids app state (key: `questv3`)

## Design Approach
- Currently: gradient backgrounds, glassmorphism, CSS animations
- Planned: full redesign (style TBD)
- Responsive design via media queries
- No CSS framework — hand-written CSS

## Conventions
- Single shared `style.css` for the main site
- Kids page uses inline `<style>` block
- Inline `<script>` for page-specific JS
- Emoji-based icons (no icon library)
- No minification or build step — deploy source directly
