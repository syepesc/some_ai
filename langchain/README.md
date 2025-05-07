# How-tos

## How-to run the project

1. [Install mise](https://mise.jdx.dev/installing-mise.html).
2. Run `poetry install` this will install the tools listed in `.tool-versions`.

## How-to run a jupyter notebook

1. Run `poetry run jupyter notebook`.
2. Open your browser on `http://localhost:8888`.
3. Select the notebook you want to run.

## How-to run python linter

1. To lint and format code run: `poetry run black .`.`.
2. For format and lint check in CI run: `poetry run black . --check`.
