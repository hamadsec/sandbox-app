# sandbox-app

Throwaway static site used by AquaSoft to prove the agent delivery chain (fork PRs, CI, review, local demo, GitHub Pages).

This repository is **public** by design. Nothing secret ever belongs here.

## About

sandbox-app is a small, public demo app used by AquaSoft to exercise its fork/PR/CI flow: changes arrive as pull requests from a bot fork, CI checks them, and the owner reviews and merges. It is a throwaway static site — the delivery chain it exercises matters more than the code itself.

## Local run

    npx serve src   # or: python3 -m http.server --directory src 4100

## How changes arrive

Agents work on the bot's fork (`masterspark-hamad/sandbox-app`) and open pull requests here. Only the owner merges. Workflow files are owner-only.
Verified by Onni (Engineer-1) on 2026-10-20.
