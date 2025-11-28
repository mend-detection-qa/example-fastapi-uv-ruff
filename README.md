1. gustavocadev/example-fastapi-uv-ruff
URL: https://github.com/gustavocadev/example-fastapi-uv-ruff
Stars: 0
Type: REST API / Web Application Starter
UV Version: 0.9.x
Python Version: 3.10+
Main Dependencies: FastAPI, Ruff
Key Features: Minimal starter template, VSCode integration
Why Analyzed: Demonstrates simplest FastAPI + uv setup



# Python FastAPI + ruff and uv package manager

This is a simple example of a FastAPI project using the ruff and uv package manager.

To run this project, you need to have the ruff and uv package manager installed. You can install it using the following command:

```bash
pip install uv
```
With uv installed, you can install the project dependencies using the following command:

```bash

uv add "fastapi[standard]"
```
Note: You don't need to use pip anymore, uv will take care of everything.

After installing the uv package manager, you can run the project using the following command:

```bash
uv run fastapi dev .\main.py
```

Additionally, you can format the code using ruff:

```bash
uv pip install ruff
```
Download the vscode extension too! [ruff-vscode](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)
