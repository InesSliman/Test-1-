# AGENTS.md

This repository is a small static web app for a matchmaking-style quiz. The project is intentionally lightweight and uses plain HTML, CSS, and JavaScript rather than a framework or build pipeline.

## Project structure

- [README.md](README.md): project overview
- [index.html](index.html): landing page and overall layout shell
- [quiz.html](quiz.html): main quiz logic, selection handling, and result display

There is no package manager, bundler, or automated test suite in this repo. Changes should stay simple, browser-native, and easy to verify by opening the page in a browser.

## Working conventions

- Prefer plain HTML/CSS/JavaScript for all edits unless the repo clearly requires otherwise.
- Keep UI changes self-contained in the existing page structure and style system.
- Preserve the current DOM structure, class names, and IDs if the quiz logic depends on them.
- Favor small, readable updates over introducing new tooling or abstractions.
- Maintain the existing visual style: clean card layout, restrained neutral palette, and subtle accent colors.

## Validation

- Open the page directly in a browser or serve the folder with a basic static server when extra inspection is needed.
- Check that the landing page renders correctly and that each quiz step advances as expected.
- Verify the final result card appears and content is consistent after answering questions.
- For UI changes, prefer quick browser verification over adding new tooling that the project does not already use.
