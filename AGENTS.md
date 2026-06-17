# AGENTS.md

## Cursor Cloud specific instructions

This repository is a **GitHub profile README** repo, not an application codebase.

- The only tracked file is `README.md`, which renders on the owner's GitHub profile page.
- There is **no** package manager, build system, dependency manifest, lint config, test suite, or runnable service. Nothing needs to be installed and no update/startup script is warranted.
- `README.md` is mostly inline HTML (`<img>`/`<div>`) plus a few Markdown headings, and references remote images (github-readme-stats, shields.io badges, devicon logos, the snake-animation SVG). Those images require network access and are rendered server-side by GitHub.
- To preview locally: render `README.md` to HTML and open it in a browser (the remote badge/stat images will load if the network allows). Editing the profile = editing `README.md`.
