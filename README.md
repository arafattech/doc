# How to Run the Documentation

This documentation project is built using [MkDocs](https://www.mkdocs.org/).

## Prerequisites

- Python 3.x
- pip

## Installation

Since the system python is managed, it is best to use a virtual environment:

1. Create a virtual environment:
   ```bash
   python3 -m venv venv
   ```

2. activate the environment (optional, but recommended):
   ```bash
   source venv/bin/activate
   ```

3. Install requirements inside the environment:
   ```bash
   pip install mkdocs mkdocs-material
   ```

## Running Locally

1. Navigate to the project directory:
   ```bash
   cd /var/www/html/doc
   ```

2. Start the development server (using the virtual environment):
   ```bash
   ./venv/bin/mkdocs serve
   ```
   Or if you activated the environment:
   ```bash
   mkdocs serve
   ```

3. Open your browser and go to `http://127.0.0.1:8000/`.

4. /venv/bin/mkdocs serve -a 0.0.0.0:8000

## Building for Production

To build the static site:
```bash
mkdocs build
```
The output will be in the `site/` directory.
