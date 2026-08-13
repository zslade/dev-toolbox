# Python Cheatsheet

## uv

```bash
uv sync # create venv, lock and install dependencies
uv add --dev package_name # add package to pyproject.toml
uv run main.py # run a script
uv run python # run a python REPL
uv run pytest # run a CLI tool
uv run ruff check . # and other commands below
uvx run tool_name # downloads package to temporary cache and runs as an isolated global utility
```

## ruff

```bash
ruff check .
ruff check . --fix
ruff format .
```

## venv

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Execution

```bash
python3 python_script.py # run python script from terminal
python3 -c "import sys; print('\n'.join(sys.path))" # run string as python code
python3 # open a REPL
exit() or Ctrl + D # to exit REPL
```