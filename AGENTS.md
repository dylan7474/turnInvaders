# AGENTS Guide for turnInvaders

This file provides quick guidance for future AI coding agents working in this repository.

## Project layout
- `index.html`: Entire game (markup, styles, and JavaScript logic) in one file.
- `README.md`: Player-facing project overview and setup instructions.
- `LICENSE`: MIT license text.

## Working conventions
- Keep the game runnable as a static site without adding mandatory build tooling.
- Prefer small, focused edits to `index.html`; avoid large rewrites unless requested.
- If adding features, preserve keyboard and button parity where practical.
- Keep retro arcade theme and terminology consistent (ships, sectors, AP, etc.).

## Validation checklist
- Confirm the page still loads in a browser.
- Confirm core controls still work: movement, rotate, fire, shield, and end turn.
- Update `README.md` when controls or setup instructions change.

## Documentation expectations
- Document user-visible features in plain language.
- Include exact local run commands when setup steps change.

## Git hygiene
- Use descriptive branch names and concise commit messages.
- Commit only related changes together.
