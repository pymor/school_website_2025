# pyMOR School 2025 Website

## Building locally

```bash
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
nikola build
nikola serve -b
```

## Deploying to GitHub Pages

```bash
nikola github_deploy
```
