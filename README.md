# Barrington Popo

I build and review evaluation tasks for large language models. Freelance, based in London, working through data annotation platforms for AI lab clients. Most days that means agentic coding evals. I write tasks meant to make strong models fail and build the Docker environments they run in. The rest of the time goes on grading model output against rubrics I design, and on reviewing other people's submissions before they ship.

Client work sits under NDA, so none of it appears here. Everything below was rebuilt from scratch on my own time to show the same skills.

## What's here

[llm-eval-harness](https://github.com/barringtonpopo/llm-eval-harness) is a small Python CLI that runs a model against a folder of task files, grades the answers with deterministic checks and an LLM judge, and writes a report. Tested, CI on every push, runs offline out of the box.

[funding-note](https://github.com/barringtonpopo/funding-note) pulls live perp funding rates from Hyperliquid and dYdX, computes cross-venue spreads, and has an LLM write the analyst note. Every figure in the note is then verified against the source data, so a model that invents a number gets caught.

[swe-task-pack](https://github.com/barringtonpopo/swe-task-pack) holds original SWE-bench-style task instances built from real, recently fixed bugs in public Python libraries, each with fail-to-pass tests, a golden patch and a harness that re-proves the task discriminates on every push.

[terminal-bench-task](https://github.com/barringtonpopo/terminal-bench-task) is an original agent-evaluation task in the Harbor format, a messy two-venue funding data pipeline with decoy observations and an empty-field trap, shipped with an oracle solution and a verifier that re-proves the task from scratch on every push.

## Before this

Five years as an investment analyst in DeFi and on-chain analytics at BMP Digital, with an MBA before that. Along the way I ran a Solana validator on AWS and hunted bugs in Ethereum and Solana smart contracts through bounty programmes.

## Day to day

Python, Docker, pytest and git on the eval side. Dune Analytics and raw on-chain data on the crypto side.

## Contact

[LinkedIn](https://www.linkedin.com/in/bpopo/) is the quickest way to reach me.
