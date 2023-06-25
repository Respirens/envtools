# envtools

> Simple tool for environment variables

### Features

- Dumping environments
- Joining .env files to one string
- Generating environment activation scripts from .env files

### Installation

```bash
pip install envtools
```

### Usage

```bash
# Dump environment
python -m envtools dump

# Dump environment to file
python -m envtools dump .env

# Join .env file
python -m envtools join .env

# Generate script
python -m envtools script .env
```