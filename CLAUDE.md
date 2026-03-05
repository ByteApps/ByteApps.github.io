# CLAUDE.md

## Project Overview

Personal professional website for Salvador Guerrero, hosted on GitHub Pages.

- **URL**: [guerrero.vip](https://guerrero.vip)
- **Stack**: Pure HTML, CSS, JavaScript — no frameworks or build tools
- **Fonts**: Inter (sans-serif), JetBrains Mono (monospace) via Google Fonts
- **Theme**: Dark orange/Bitcoin-inspired palette (`--accent: #c47a1a`)

## Directory Structure

```
├── index.html          # Single-page site (all HTML, CSS, JS inline)
├── assets/
│   └── profile.jpg     # Profile photo used in the hero section
├── .claude/
│   └── launch.json     # Dev server config (Python http.server on port 8080)
├── .gitignore
├── LICENSE
├── README.md
└── CLAUDE.md
```

## Development

Run a local dev server:

```bash
python3 -m http.server 8080
```

Or use the Claude Code preview with the `static-site` configuration in `.claude/launch.json`.

## Key Sections

- **Hero**: Profile photo, name, title, tagline, social links
- **About**: What I Do, Interests, Education, Technologies cards
- **Tools & Projects**: Open source project cards linking to GitHub repos
- **Blog**: Articles from Medium (@ObjSal)
- **Games**: Game project cards
- **Experience**: Professional timeline from LinkedIn

## Notes

- All content is static (no API calls or dynamic fetching)
- Profile data was sourced from LinkedIn, GitHub, Medium, and X
- The site is a single `index.html` file with all styles and scripts inline
- Responsive design with a mobile hamburger menu
