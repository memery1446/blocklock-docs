# ethlock-setup

Here's the EthLock doc — paste it into your `ethlock` instance:

---

# Documentation Setup — EthLock

## Overview

This document describes how the EthLock documentation system was set up using JetBrains Writerside, hosted on GitHub Pages as part of the BlockLock dedicated documentation repository.

## Tools Used

- **IDE:** WebStorm
- **Documentation Plugin:** Writerside by JetBrains
- **Repository:** blocklock-docs (shared dedicated docs repo on GitHub)
- **Publishing:** GitHub Pages

## About EthLock

EthLock is a quantum-resistant Ethereum custody system featuring a 7-service architecture including Python Brain orchestration, Node.js eth-service, React frontend, PostgreSQL database, and smart contracts supporting both single-signature and multisig functionality. EthLock is patent-pending, co-invented by Mark and David DeMayo (CTO, Syntropy Software).

## Repository Structure

EthLock documentation lives inside the `blocklock-docs` repository as a separate Writerside instance, keeping it versioned independently from the EthLock application codebase while remaining logically grouped with all BlockLock platform documentation.

## Writerside Configuration

The EthLock instance was created inside the Writerside panel:

- **Help Instance:** EthLock (ID: ethlock)
- **Parent Repo:** blocklock-docs
- **Related Instance:** BlockLock Docs (ID: bl-docs)

## Content Workflow

1. Draft content in plain text using an AI assistant (Claude or ChatGPT)
2. Paste into the EthLock Writerside instance
3. Writerside automatically formats and adds it to the navigation
4. Commit and push to `blocklock-docs`
5. GitHub Pages publishes the updated docs automatically

## Next Steps

- Add GitHub Actions deploy.yml for automated publishing to GitHub Pages
- Document EthLock system architecture and 7-service overview
- Document smart contract design and quantum-resistance approach
- Document subscription tiers and job management system
- Document patent filing and technical IP overview

---

