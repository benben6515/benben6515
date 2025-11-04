# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **GitHub Profile README repository** (benben6515/benben6515), which displays on the user's GitHub profile page at github.com/benben6515. It is not a traditional codebase but rather a personal branding and portfolio showcase.

## Repository Purpose

- Display professional profile information on GitHub
- Showcase technical skills and technology stack
- Link to external content (ErrorBaker blog articles, reading list)
- Demonstrate completed coding challenges and exercises
- Present dynamic GitHub statistics

## Key File

**README.md** - The sole content file that renders on the GitHub profile page

## Tech Stack Displayed

**Primary Focus:** Front-end development with React/Redux, Vue/Vuex

**Currently Learning:** Vim, TypeScript, Clean Code

**Backend:** Node.js, Express, MongoDB, MySQL, PostgreSQL

**Styling:** Bootstrap, Sass, Tailwind CSS

**Creative Coding:** P5.js

## Content Structure

The README.md uses a highly structured format:

1. **Header Section** - Name, badges (Lidemy bootcamp, Codewars rank, email)
2. **Stats Section** - GitHub stats and language graphs (via github-readme-stats API)
3. **About Section** - Personal introduction, interests, learning goals
4. **Technology Showcase** - Organized by proficiency level:
   - Main Languages and Tools (HTML5, CSS3, JavaScript, TypeScript, Git, Linux)
   - Framework (React, Redux, Vue)
   - Style (Bootstrap, Sass, Tailwind)
   - Second Languages and Tools (Node.js, Express, MongoDB, MySQL, PostgreSQL)
   - Basic Languages and Tools (C++, Python)
5. **Records Section** - Collapsible details with completed challenges (LIOJ, HTTP Challenge, CSS Diner, Flexbox Froggy)

## Development Workflow

Since this is a profile repository with no build process:

- **Editing:** Direct markdown/HTML editing of README.md
- **Preview:** Use GitHub's preview or markdown preview tools
- **Commit:** Changes go directly to main branch
- **No dependencies:** No package.json, no build tools, no runtime requirements

## Markdown Conventions

- Heavy use of **HTML within Markdown** for advanced layout control
- **External image embedding** via CDN (devicons, vectorlogo.zone)
- **Dynamic content** through GitHub Stats API and profile counters
- **Alignment controls** using `<p align="center">` and `<div align="center">`
- **Icon sizing:** Consistent 40x40 pixel dimensions for technology icons
- **Theme:** Dracula theme for stats graphs

## External Integrations

- **GitHub Stats:** github-readme-stats-sigma-five.vercel.app
- **Profile Counter:** profile-counter.glitch.me
- **Badges:** shields.io, codewars.com badges
- **Icons:** devicons.github.io, vectorlogo.zone

## Git Workflow

- All recent commits follow pattern: "Update README.md"
- No branching strategy needed
- Direct commits to main branch
- Single-file modifications only

## Important Links

- Blog: [ErrorBaker 技術共筆部落格](https://blog.errorbaker.tw/)
- Author's articles: https://blog.errorbaker.tw/posts/benben/
- Reading list: https://hackmd.io/@benben6515/reading-list
- P5.js animation: https://openprocessing.org/sketch/1194583

## Common Edits

When updating this profile:

1. **Skills update:** Modify the technology icon sections to reflect new skills
2. **Learning focus:** Update the "I'm currently learning" section (line 23)
3. **Stats refresh:** GitHub stats update automatically; no manual action needed
4. **New achievements:** Add to the Records section (lines 108-120)
5. **Contact info:** Update badges in header (line 1)

## Notes for Claude Code

- This is NOT a software project requiring builds, tests, or deployments
- Primary task: Content editing and markdown formatting
- No security concerns (no executable code, API keys, or sensitive data)
- Preview changes before committing to ensure proper rendering
- Maintain existing visual style and structure when making updates
