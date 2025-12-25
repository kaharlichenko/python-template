# Python Project Template

A [Copier](https://copier.readthedocs.io/) template for Python projects with `uv` and `mise`.

## Features

- Tool management via `mise` (including Python itself)
- Python dependency management with `uv`
- Optional Docker image builds

## Usage

### Prerequisites

To use this template you need copier version 9.11.0 or later.

**Option 1: Install copier via mise**

```bash
mise use -g copier@9.11
```

**Option 2: Install copier via uv**

```bash
uv tool install "copier>=9.11"
```

**Option 3: Install copier via pipx**

```bash
pipx install "copier>=9.11"
```

**Option 4: Use copier without installation via uvx**

```bash
# No installation needed - uvx will run copier on demand
uvx "copier>=9.11" copy gh:kaharlichenko/python-template /path/to/your-project
```

### Create a New Project

**If copier is installed:**

```bash
copier copy gh:kaharlichenko/python-template /path/to/your-project
```

Or from a local clone:
```bash
copier copy . /path/to/your-project
```

**Using uvx without installation:**
```bash
uvx "copier>=9.11" copy gh:kaharlichenko/python-template /path/to/your-project
```
