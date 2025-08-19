# Python Project Template

A modern Python project template with FastAPI, uv, and development tools.

## Setup

Install dependencies:
```bash
just setup
```

Run the application:
```bash
python main.py
```

## Development

Run linting and formatting:
```bash
just lint
```

Run tests:
```bash
just test
```

Clean cache files:
```bash
just clean
```

## Dependencies

- FastAPI - Web framework
- Pydantic - Data validation  
- Uvicorn - ASGI server
- Ruff - Linting and formatting
- pytest - Testing

## Tools

- **uv** - Package management
- **just** - Command runner
- **pre-commit** - Git hooks
- **ruff** - Code quality

## Structure

```
project/
├── main.py           # Entry point
├── tests/            # Test files
├── pyproject.toml    # Dependencies
├── justfile          # Commands
└── docs/             # Documentation
```
