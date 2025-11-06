![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![uv](https://img.shields.io/badge/uv-4baaaa?style=for-the-badge&logo=github)


# Multiagent system 
This is a multiagent system built using [uv](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer) and [agno](https://docs.agno.com/).


## ◻️ Setup 

◽  **Step 1** Install [uv](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer)

◽  **Step 2**  Create a virtual environment

```bash
uv venv .venv 
```

◽  **Step 3** Install packages into the current environment.

If you have a pyproject.toml file with all the dependencies. Just run and the environment will be ready

```bash
uv pip install -e .
```

## ◻️ Usage
```bash
uv run main.py
```

Go to http://127.0.0.1:8046/
