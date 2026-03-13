# docs

Zensical documentation template.

## Usage

Install with pip:

```bash
git clone git@github.com:qiekn/docs.git my-project
cd my-project

python -m venv .venv
.venv\Scripts\activate
pip install zensical

zensical serve
```

Install with uv:

```bash
git clone git@github.com:qiekn/docs.git my-project
cd my-project

uv init
uv add --dev zensical

uv run zensical serve
```

## Structure

```
.
├── docs/
│   ├── images/
│   ├── stylesheets/
│   └── index.md
├── overrides/
│   └── partials/
│       └── copyright.html
├── zensical.toml
└── .gitignore
```
