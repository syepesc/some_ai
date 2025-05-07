# How-tos

## How-to run the project

1. [Install mise](https://mise.jdx.dev/installing-mise.html).
2. Run `poetry install` this will install the tools listed in `.tool-versions`.
3. Set your env variables. I use `direnv`.
    - Create `.envrc` file in root project folder.
    - Set your envs like `export ENV="your_env"`.
    - Run: `direnv allow` to export your envs.

## How-to run a jupyter notebook

1. Read and execute the [How-to run the project](#how-to-run-the-project) section.
2. Run `poetry run jupyter notebook`.
3. Open your browser on `http://localhost:8888`.
4. Select the notebook you want to run.

## How-to run python linter

1. To lint and format code run: `poetry run black .`.
2. For format and lint check in CI run: `poetry run black . --check`.
