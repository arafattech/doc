# How to Run the Documentation

This documentation project is built using [MkDocs](https://www.mkdocs.org/).

## Prerequisites

- Python 3.x
- pip

## Installation

1. Install MkDocs and the Material theme:
   ```bash
   pip install mkdocs mkdocs-material
   ```

## Running Locally

1. Navigate to the project directory:
   ```bash
   cd /var/www/html/doc
   ```

2. Start the development server:
   ```bash
   mkdocs serve
   ```

3. Open your browser and go to `http://127.0.0.1:8000/`.

## Building for Production

To build the static site:
```bash
mkdocs build
```
The output will be in the `site/` directory.
