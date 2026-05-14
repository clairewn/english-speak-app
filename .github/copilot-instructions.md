# Copilot Instructions for this Repository

This repository is a tiny static site. These instructions tell an AI coding agent how to be immediately productive here.

Summary
- Purpose: simple static frontend served by `index.html` (no backend). Use `README.md` for high-level notes.
- Primary files: `index.html`, `README.md`.

What to edit
- Frontend/UI: `index.html` — all HTML, CSS, and small JS (if any) live in this single file.
- Documentation: `README.md` — update when changing user-facing features or local run instructions.

Build / Run / Debug
- There is no build system or package manager in this repo. Test locally by serving the directory:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in a browser
```

Project-specific patterns and conventions
- Single-file frontend: Avoid creating complex build pipelines unless the user asks. Keep small UI changes in `index.html`.
- Minimal external dependencies: There are none tracked here. If adding a dependency, update the `README.md` with install and run instructions.
- Keep edits conservative: Because this repo is tiny, prefer minimal, well-scoped changes and update `README.md` to document them.

Integration points and external services
- None detected. If you add integrations (APIs, analytics, CDNs), document endpoints and keys in `README.md`, and never commit secrets.

Commit / PR guidance
- Use short, descriptive commit messages (e.g., "Fix typo in header", "Add contact link to homepage").
- For multiple logical changes, split into small PRs so reviewers can test locally by opening `index.html` or running the simple server above.

Examples (concrete edits)
- Change text: edit the header paragraph in `index.html` and update `README.md` to reflect the new copy.
- Add a stylesheet: add `styles.css` at repo root, link it from `index.html`, and note the change in `README.md`.

What not to do
- Do not introduce complex build tooling (Webpack, Node) without explicit user approval.
- Do not add or commit secrets or credentials.

If something is unclear
- Ask the user whether they want a simple static site maintained or a migration to a multi-file/frontend-tooling project.

Next steps for reviewers
- Verify `index.html` changes by running the local server and opening the page.
- If adding new files or tooling, request explicit confirmation and update this document.

---
If you'd like, I can adapt these instructions to include a preferred commit style, test checklist, or convert the site to a small build setup (e.g., Vite). What should I add or clarify?
