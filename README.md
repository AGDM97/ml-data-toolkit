# ml-data-toolkit

Professional-grade starter kit for ML data work: download, validate, preprocess and version datasets.

## Why this repo exists
This project is part of my AI Engineer learning path. It focuses on engineering fundamentals that support model training:
- reproducible environments
- code quality (lint/format/tests)
- CI automation

## Current status (Week 1)
✅ Repo scaffold using src-layout  
✅ ruff + pytest + pre-commit  
✅ GitHub Actions CI (lint, format-check, tests)

## Local setup (Windows PowerShell)
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements-dev.txt
python -m pip install -e .
pre-commit install
pytest -q
