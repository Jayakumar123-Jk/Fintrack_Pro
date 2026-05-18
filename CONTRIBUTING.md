# Contributing to Fintrack Pro

Thanks for your interest in improving Fintrack Pro. This document covers the basics for getting set up and submitting changes.

## Getting started

1. Fork the repository on GitHub.
2. Clone your fork locally.
3. Install dependencies (see [SETUP_GUIDE.md](./SETUP_GUIDE.md) and the root `package.json`).
4. Create a feature branch:
   ```bash
   git checkout -b feat/short-description
   ```

## Branch naming

Use a short prefix that describes the change:

- `feat/` — new feature
- `fix/` — bug fix
- `docs/` — documentation only
- `chore/` — tooling, build, or config
- `refactor/` — internal changes with no behavior difference

## Commit messages

- Keep the subject under ~72 characters.
- Use the imperative mood ("Add health endpoint", not "Added health endpoint").
- Reference an issue number in the body when applicable.

## Pull requests

- Keep PRs focused — one logical change per PR.
- Describe what changed and why.
- Make sure the project builds (`npm run dev` for local dev, `docker-compose up --build` for the full stack).
- Lint the frontend before pushing:
  ```bash
  cd frontend && npm run lint
  ```

## Reporting bugs

Open a GitHub issue with:

- What you did
- What you expected
- What actually happened
- Environment (OS, Node version, browser if relevant)

## Code of conduct

Be respectful. Assume good intent. Keep feedback focused on the code.
