# Contributing — AI Security Research

Thanks for wanting to contribute. This repo is intentionally lightweight. Follow these simple steps:

## Quick rules
- Keep entries factual, non-spammy, and relevant to AI/LLM/agent security.
- If a resource is a hands-on lab or PoC, include clear sandboxing / safety notes.
- Prefer authoritative sources (official docs, research papers, reputable blogs).

## How to add a resource (fast)
1. Fork the repo.
2. Edit `resources/RESOURCES.md` and add a single-line entry under the most appropriate category:
   - Format: `- Name — https://link — short 1-line description (optional)`
3. Commit and open a PR against `main`.
4. In the PR description add:
   - Why the resource is useful (1-2 lines)
   - Tags (e.g., `tool`, `lab`, `paper`, `poC`, `vulnerable`, `framework`)

## Adding labs / PoCs
- If you add a lab or PoC, include safe-run instructions and recommended sandbox (VM, container). If the PoC could be dangerous, maintainers may refuse or move it to a special `labs/unsafe` folder with strict warnings.

## Editorial process
- Small edits (typos, link fixes) will be merged quickly.
- New resource additions will be reviewed for relevance and safety.
- If there are disputes, maintainers will resolve or request changes.

## Issues
- Use Issues to request removal, report broken links, or propose larger structure changes.
- Tag new issues with `good-first-issue` if you want help from maintainers.

## Code of Conduct
Be respectful. This is a professional community resource.

