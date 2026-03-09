# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

This is a single-file web project. Each game or feature lives in its own self-contained HTML file with inline CSS and JavaScript — no build tools, no dependencies, no package manager.

To run: open the HTML file directly in a browser.

## Git workflow

All changes must be committed and pushed to GitHub after each meaningful feature or fix:

- Repository: https://github.com/MortenDyn/ClaudeCodeTest
- Branch: `main`
- After committing, always run `git push`

Commit message format:
```
<type>: <short summary>

- bullet points describing what changed
```

Common types: `feat`, `fix`, `style`, `refactor`

## Code conventions

- All HTML, CSS, and JS lives in a single `.html` file per project
- Vanilla JS only — no frameworks or libraries
- Dark theme color palette (established in `tictactoe.html`):
  - Background: `#1a1a2e`
  - Card/cell: `#16213e`
  - Accent blue: `#0f3460`
  - Red/primary: `#e94560`
  - Light blue/secondary: `#a8dadc`
