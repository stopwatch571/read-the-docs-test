# Getting Started

## Prerequisites

- Python 3.10+
- `pip` package manager

## Local Development

Install MkDocs and the Material theme:

```bash
pip install mkdocs mkdocs-material
```

Clone the repository and serve the docs locally:

```bash
git clone https://github.com/stopwatch571/read-the-docs-test.git
cd read-the-docs-test
mkdocs serve
```

Open [http://localhost:8000](http://localhost:8000) in your browser.

## Building Static Files

To build the site as static HTML:

```bash
mkdocs build
```

The output will be in the `site/` directory.
