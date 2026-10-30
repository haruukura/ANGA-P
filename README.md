# Antigravity Project

A modern Python project template set up with [`uv`](https://docs.astral.sh/uv/) and a `src/` layout.

## Project Structure

```text
Antigravity/
├── .venv/                   # Virtual environment managed by uv
├── src/
│   └── antigravity_project/
│       ├── __init__.py      # Package initializer
│       └── main.py          # Main entry point
├── .gitignore               # Git ignore rules
├── .python-version          # Target Python version
├── pyproject.toml           # Project metadata & dependencies
└── README.md                # Project documentation
```

## Getting Started

### 1. Prerequisites
Ensure you have [uv](https://docs.astral.sh/uv/getting-started/installation/) installed:
```bash
brew install uv
```

### 2. Environment Setup
Install dependencies and sync the virtual environment:
```bash
uv sync
```

### 3. Running the Application
Run the entry point using `uv`:
```bash
uv run antigravity-project
```
Or directly run the module:
```bash
uv run python -m antigravity_project.main
```
Or activate the virtual environment:
```bash
source .venv/bin/activate
python -m antigravity_project.main
```

### 4. Adding Dependencies
Add packages to your project:
```bash
uv add <package-name>
```
For development dependencies:
```bash
uv add --dev pytest ruff
```
