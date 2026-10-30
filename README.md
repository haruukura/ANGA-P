# Antigravity Project

A Python project managed with uv.

## Setup

1. Install dependencies:
```bash
uv sync
```

2. Run the application:
```bash
uv run antigravity-project
```

## Useful Commands

- Run the app: `uv run antigravity-project`
- Run module directly: `uv run python -m antigravity_project.main`
- Add a dependency: `uv add <package>`
- Add a dev dependency: `uv add --dev <package>`
- Remove a dependency: `uv remove <package>`
- Sync environment: `uv sync`
- Activate virtual environment: `source .venv/bin/activate`

## Note

The package inside `src/` is named `antigravity_project` to avoid conflicts with Python's built-in `antigravity` module.
