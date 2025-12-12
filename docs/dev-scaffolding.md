# dev

Fast project scaffolding tool for Python and React projects.

## Install

```bash
chmod +x dev
sudo mv dev /usr/local/bin/dev
```

## Usage

```bash
dev <project-type> <directory> [flags]
```

### Project Types
- `python-ml` - ML project with notebooks and data folders
- `python-fastapi` - FastAPI backend
- `python-science` - Data science project
- `vite-react` - Vite + React frontend

### Flags
- `-g` - Initialize git repo
- `-v` - Create virtual environment (default: uv, use `-v venv` for standard venv)
- `-t` - Add Tailwind CSS v4 (vite-react only)

## Examples

```bash
# Python ML project with git and venv
dev python-ml my-project -g -v

# FastAPI with standard venv
dev python-fastapi api -g -v venv

# React with Tailwind
dev vite-react frontend -g -t
```
