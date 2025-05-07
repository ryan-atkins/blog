# blog

[![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

## Quick Start

Install with [uv](https://github.com/astral-sh/uv)

```bash
uv install
```

Run locally

```bash
➜ blog (main) ✗ uv run mkdocs serve 
INFO    -  Building documentation...
INFO    -  Cleaning site directory
INFO    -  Documentation built in 0.21 seconds
INFO    -  [14:53:16] Watching paths for changes: 'docs', 'mkdocs.yml'
INFO    -  [14:53:16] Serving on http://127.0.0.1:8000/
```

## Commands

* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

The following shows the layout of the files in this template. Note that you can
configure Material for MkDocs to use a different layout, this is simply the
default.

```
mkdocs.yml          # The configuration file.
docs/
    index.md        # The blog homepage.
    posts/          # the place to put your posts
        drafts/     # WIP draft blog posts
    .authors.yml    # Author information to be added to posts
```
