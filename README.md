# Antigravity Project

A modern Python project template set up with [`uv`](https://docs.astral.sh/uv/) and a `src/` layout.

> **Note:** The package is named `antigravity_project` inside `src/` to avoid naming conflicts with Python's built-in standard library `antigravity` module.

---

## Project Structure

```text
Antigravity/
├── .venv/                      # Virtual environment managed by uv
├── src/
│   └── antigravity_project/
│       ├── __init__.py         # Package initializer
│       └── main.py             # Main entry point
├── .gitignore                  # Git ignore rules
├── .python-version             # Target Python version
├── pyproject.toml              # Project metadata & dependencies
├── README.md                   # Project documentation
└── uv.lock                     # Deterministic dependency lockfile
```

---

## Useful Commands (Quick Reference)

| Task | Command |
| :--- | :--- |
| **Run the application** | `uv run antigravity-project` |
| **Run module directly** | `uv run python -m antigravity_project.main` |
| **Add dependency** | `uv add <package-name>` |
| **Add dev dependency** | `uv add --dev <package-name>` (e.g. `pytest`, `ruff`) |
| **Remove dependency** | `uv remove <package-name>` |
| **Sync environment** | `uv sync` |
| **Activate virtualenv** | `source .venv/bin/activate` |

---

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
Or activate the virtual environment manually:
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
