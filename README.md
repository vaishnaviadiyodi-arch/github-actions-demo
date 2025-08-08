# GitHub Actions CI Demo

![CI](https://github.com/vaishnaviadiyodi-arch/github-actions-demo/actions/workflows/main.yml/badge.svg)

A tiny repo to showcase a professional GitHub Actions pipeline (lint → test → deploy-sim).

## What this repo demonstrates
- Multi-step CI with GitHub Actions
- Linting with flake8, testing with pytest
- PR-friendly flow (templates, branch protection)
- Security (CodeQL) and dependency automation (Dependabot) *(coming next)*

## Run locally
```bash
python -m pip install -r requirements.txt
pytest -q tests

