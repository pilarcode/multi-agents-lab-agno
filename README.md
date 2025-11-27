![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![uv](https://img.shields.io/badge/uv-4baaaa?style=for-the-badge&logo=github)


# Table of Contents
- [Introduction](#introduction)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contribution](#contribution)

## Introduction
This project implements a multi-agent system utilizing the [uv](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer) and [agno](https://docs.agno.com/) libraries. Designed for scalability and efficiency, this system facilitates robust interactions between agents within a simulated environment.

## System Requirements
- Python 3.11 or newer
- uv library
- agno library

## Installation
Follow these steps to set up the project:

1. **Install uv**  
   Refer to the [installation guide](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer) for detailed instructions.

2. **Create a Virtual Environment** 
   ```bash
   uv venv .venv
   ```

3. **Install Project Dependencies**
   Ensure you have a `pyproject.toml` file with all dependencies listed, then execute:
   ```bash
   uv pip install -e .
   ```

## Usage
To run the system, use the following command:

```bash
uv run main.py
```

Navigate to [http://127.0.0.1:8046/](http://127.0.0.1:8046/) to access the application.

## Contribution
Contributions are welcomed! Please follow the guidelines below:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push your branch (`git push origin feature-branch`).
5. Open a Pull Request.

Ensure that your code follows the project's coding standards and includes tests where applicable.



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


