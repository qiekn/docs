# docs

Documentation template collection with live previews on GitHub Pages.

**Live preview:** [qiekn.github.io/docs](https://qiekn.github.io/docs/)

## Templates

| Template | Preview | Clone |
|----------|---------|-------|
| Zensical | [Preview](https://qiekn.github.io/docs/zensical/) | `git clone -b zensical git@github.com:qiekn/docs.git` |
| mdBook | [Preview](https://qiekn.github.io/docs/mdbook/) | `git clone -b mdbook git@github.com:qiekn/docs.git` |

## Branch Structure

- **`main`** — Landing page + CI/CD (aggregates and deploys all templates)
- **`zensical`** — Zensical documentation template
- **`mdbook`** — mdBook documentation template

## Usage

Clone a specific template branch to start a new project:

```bash
# Zensical template
git clone -b zensical git@github.com:qiekn/docs.git my-docs

# mdBook template
git clone -b mdbook git@github.com:qiekn/docs.git my-book
```
