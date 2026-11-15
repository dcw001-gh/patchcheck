# PatchCheck
A reproducible evaluation tool for AI-generated bug fixes using independent tests.

## Status

Initial development setup. The evaluation runner is not implemented yet.

## Requirements

- Python 3.13
- Git

## Development Setup

The following commands are for Windows Command Prompt.

```bat
py -3.13 -m venv .venv
.venv\Scripts\activate.bat
python -m pip install -r requirements-dev.txt
```

## Verify the Development Environment

```bat
python -m pip check
python -m pytest --version
```