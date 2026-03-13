# docs

Zensical documentation template.

## Usage

```bash
git clone git@github.com:qiekn/docs.git my-project
cd my-project

python3 -m venv .venv
source .venv/bin/activate
pip install zensical

zensical serve
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
