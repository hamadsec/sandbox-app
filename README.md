# sandbox-app

Throwaway static site used by Verso Labs to prove the agent delivery chain (fork PRs, CI, review, local demo, GitHub Pages).

This repository is **public** by design. Nothing secret ever belongs here.

## Local run

    npx serve src   # or: python3 -m http.server --directory src 4100

## How changes arrive

Agents work on the `verso-agents` fork and open pull requests here. Only the owner merges. Workflow files are owner-only.
