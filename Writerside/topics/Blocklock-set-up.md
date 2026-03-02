# Blocklock set up

Here's your first doc — plain text, ready to paste into Writerside:

---

# Documentation Setup — BlockLock Docs

## Overview

This document describes how the BlockLock documentation system was set up using JetBrains Writerside, hosted on GitHub Pages via a dedicated documentation repository.

## Tools Used

- **IDE:** WebStorm
- **Documentation Plugin:** Writerside by JetBrains
- **Repository:** blocklock-docs (separate dedicated repo on GitHub)
- **Publishing:** GitHub Pages

## Repository Setup

A standalone GitHub repository named `blocklock-docs` was created to house all documentation separately from the main codebase. This keeps docs versioned independently and cleanly separated from application code.

The repo was cloned locally via terminal and opened in WebStorm.

## Writerside Configuration

Two documentation instances were created inside the Writerside panel:

- **BlockLock Docs** (ID: bl-docs) — covers the ui.blocklock.ai platform
- **EthLock** (ID: ethlock) — covers the core EthLock custody system

Each instance maintains its own navigation structure and table of contents automatically.

## Content Workflow

1. Draft content in plain text using an AI assistant (Claude or ChatGPT)
2. Paste into the appropriate Writerside instance
3. Writerside automatically formats and adds it to the navigation
4. Commit and push to `blocklock-docs`
5. GitHub Pages publishes the updated docs automatically

## Next Steps

- Add GitHub Actions deploy.yml for automated publishing to GitHub Pages
- Begin adding technical documentation for EthLock architecture
- Begin adding platform documentation for ui.blocklock.ai

---

