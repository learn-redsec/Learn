# RedSec Learn

RedSec Learn is a small Mintlify learning hub for red team fundamentals, safe labs, and beginner-friendly study paths.

## Prerequisites

- [Node 24 or higher](https://nodejs.org/en/download)
- [pnpm 10](https://pnpm.io/installation#using-npm)
- `corepack`, which is included with Node

## Setup

1. Install Node 24. With `nvm`, run `nvm install`.
2. Enable package manager shims with `corepack enable pnpm`.
3. Install dependencies with `pnpm install`.
4. Start the local site with `pnpm run dev`.

The local site runs at `http://localhost:3333/`.

## Content

The visible learning experience is configured in `docs.json` and currently points to the small set of pages in `start.mdx` and `learn/`.

The old imported source pages are still in the repository for later cleanup, but they are not part of the RedSec Learn navigation.
