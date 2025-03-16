# Getting Started

This guide will help you get started with MkDocs and show you how to create and deploy your own documentation.

## Prerequisites

- Python 3.x
- pip (Python package manager)
- Git

## Installation

1. Install MkDocs and the Material theme:
```bash
pip install mkdocs-material
```

2. Clone this repository:
```bash
git clone <your-repository-url>
cd <repository-name>
```

## Local Development

1. Start the live-reloading docs server:
```bash
mkdocs serve
```

2. Open your browser and visit `http://127.0.0.1:8000/`

3. Edit the documentation files in the `docs/` directory. The browser will automatically reload to preview your changes.

## Project Structure

- `mkdocs.yml` - Configuration file
- `docs/` - Documentation files
    - `index.md` - Homepage
    - `getting-started.md` - This guide
    - `about.md` - About page

## Writing Documentation

MkDocs uses Markdown syntax. Here are some examples:

### Headers

```markdown
# H1 Header
## H2 Header
### H3 Header
```

### Lists

```markdown
- Item 1
- Item 2
    - Subitem 2.1
    - Subitem 2.2
```

### Code Blocks

\```python
def hello_world():
    print("Hello, World!")
\```

### Links

```markdown
[Link Text](https://example.com)
```

## Deployment

The documentation is automatically deployed to GitHub Pages when you push to the main branch. The deployment is handled by GitHub Actions. 