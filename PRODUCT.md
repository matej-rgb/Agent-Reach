# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Delegated: Astro, output as a static site. The first surface is a content-led landing page, so Astro ships near-zero JavaScript by default, deploys to any static host, and still allows interactive islands (for example a live terminal demo) where they are needed. Revisit if an app or dashboard joins this repository.

## Users

Developers who build AI agents (in Claude Code, Cursor, or other agent and MCP-capable tools) and need those agents to read the live internet. They are setting up or extending an agent and want it to search and read sources it cannot reach today, without signing up for and paying for a pile of separate APIs.

## Product Purpose

Agent-Reach gives AI agents reach into the live internet: social platforms and the open web. Success means a developer can give their agent working access to these sources in minutes, and the agent then searches and reads them on its own.

## Positioning

One toolkit covers both social platforms and the open web. The agent can install and configure it itself, it needs no paid API keys, and it plugs into existing MCP clients rather than requiring a new runtime.

## Operating Context

- Used from inside agent tooling: Claude Code, Cursor, and other MCP clients, plus a CLI or skill the agent sets up itself.
- Evaluated by developers reading a landing page, GitHub README, or terminal demo before trying it.

## Capabilities and Constraints

- Social platforms: reads and searches sources such as X/Twitter, Reddit, YouTube, LinkedIn and TikTok.
- Open web: searches the web and reads or scrapes any page, including pages that need JavaScript to render.
- Install-free setup: runs as a CLI or skill the agent configures itself, with no paid API keys required.
- MCP server: plugs into Claude, Cursor and other MCP clients.
- Undecided: the exact list of supported platforms, install commands, and the canonical repository URL for the working code. This repository currently holds only the site; confirm these before publishing them.

## Brand Commitments

Name: Agent-Reach. No other voice, logo, or identity commitments have been made yet.

## Evidence on Hand

- A working repository and demo exist, and real terminal sessions can be shown. The demo assets are not in this repository yet.
- Absent: adoption figures, GitHub star counts, testimonials, customer or partner logos, benchmarks, and pricing. Future work must not invent any of these.

## Product Principles

1. Minutes to reach: every claim and surface should shorten the path from "I found this" to "my agent can read it."
2. Show the agent doing it: prove capability with real sessions and output, not adjectives.
3. No keys, no lock-in: the free, self-configuring setup is a core promise. Never obscure it or contradict it.
4. Honest coverage: name exactly what the agent can reach. Never imply sources that aren't supported.
