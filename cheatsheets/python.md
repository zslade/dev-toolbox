# Python Cheatsheet

## uv

```bash
uv python install 3.12
uv venv
uv pip install -r requirements.txt
uv run python app.py
```

## venv

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## ruff

```bash
ruff check .
ruff check . --fix
ruff format .
```
