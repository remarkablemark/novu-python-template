# novu-python-template

[![codecov](https://codecov.io/gh/remarkablemark/novu-python-template/graph/badge.svg?token=ldtrSznCY4)](https://codecov.io/gh/remarkablemark/novu-python-template)
[![lint](https://github.com/remarkablemark/novu-python-template/actions/workflows/lint.yml/badge.svg)](https://github.com/remarkablemark/novu-python-template/actions/workflows/lint.yml)

🔔 Novu Python template built on:

- [FastAPI](https://fastapi.tiangolo.com/)

## Prerequisites

[uv](https://docs.astral.sh/uv/#installation):

```sh
brew install uv
```

## Install

Clone the repository:

```sh
git clone https://github.com/remarkablemark/novu-python-template.git
cd novu-python-template
```

Install the dependencies:

```sh
uv sync
```

## Available Scripts

In the project directory, you can run:

### `uv run pre-commit install`

Installs the pre-commit script.

### `uv run fastapi dev`

Runs the app in development mode:

- Server: http://127.0.0.1:8000
- Documentation: http://127.0.0.1:8000/docs

The server will reload if you make edits.

### `uv run fastapi run`

Runs the app in production mode.

### `uv run ruff format`

Formats the code.

### `uv run ruff check`

Lints the code.

## License

[MIT](https://github.com/remarkablemark/novu-python-template/blob/master/LICENSE)
