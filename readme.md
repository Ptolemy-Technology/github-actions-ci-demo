# GitHub Actions CI Demo

This is a tiny demo project to learn GitHub Actions CI.

## What it does

- Simple Python "calculator" module
- One unit test using `pytest`
- GitHub Actions workflow that:
  - Runs on every push and pull request
  - Sets up Python
  - Installs dependencies
  - Runs tests

## Getting started

### Run locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
pytest

