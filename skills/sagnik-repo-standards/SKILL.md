---
name: sagnik-repo-standards
description: Apply Sagnik Sen's standardized GitHub repository structure, README header/footer badges, topic taxonomy, MIT license, and GitHub Actions CI workflows.
---

# Sagnik Sen Repository Standards

Use this skill when creating, auditing, or updating any repository under `github.com/sagnik10`.

## 1. Domain Topic Taxonomy

Every public repository must include one primary category topic plus 4–6 technical/domain topics:

- `sagnik10-science`: Atmospheric, geospatial, and scientific computing
- `sagnik10-ai-ml`: AI, multimodal pipelines, security, and reinforcement learning
- `sagnik10-analytics`: Enterprise and domain data analytics pipelines
- `sagnik10-web`: Full-stack web apps, portfolios, and interactive demos
- `sagnik10-automation`: QA frameworks, scripting, and developer tooling

## 2. README Header & Footer

Wrap the top and bottom of `README.md` with idempotent `<!-- SAGNIK10-STYLE-HEADER -->` and `<!-- SAGNIK10-STYLE-FOOTER -->` markers using `shields.io` `flat-square` badges in `#275cce` (category), `#192a43` (stack), `#54647a` (license), and `#258066` (live GitHub Pages demo).

## 3. Baseline Repository Files

- `LICENSE`: MIT License (unless Apache-2.0 or another explicit license is already present).
- `.github/workflows/ci.yml`: Automated syntax/build verification on `push` and `pull_request` to `main`/`master`.
