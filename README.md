# Polly Pictures

Polly Pictures is an online shop and gallery platform for selling and showcasing artwork, including drawings and pictures. The platform allows artists to display their work and customers to browse and purchase pieces they love.

## Tech Stack

- **Backend**: Python 3.14, FastAPI, SQLAlchemy, Alembic
- **Database**: PostgreSQL (via asyncpg)

## Quick Start

### Prerequisites

- Python 3.14 or higher
- PostgreSQL database

### 1. Install uv Package Manager

Install uv using the standalone installer:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

After installation, restart your terminal.

Verify the installation:

```bash
uv --version
```

### 2. Set Up the Backend

Navigate to the backend directory:

```bash
cd pp-backend
```

Install dependencies and create a virtual environment:

```bash
uv sync
```

This command will automatically:
- Create a virtual environment
- Install all project dependencies
- Install development dependencies

### 4. Activate the Virtual Environment
```bash
source .venv/bin/activate
```
### 5. Configure pre-commit
Install pre-commit hooks:

```bash
uv run pre-commit install
```
### Other usefull commands
Run linting manually:

```bash
uv run ruff check .
```

Format code:

```bash
uv run ruff format .
```


### x. Configure Environment Variables

TBD
