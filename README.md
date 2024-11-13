# Python Template

This is a Python project template that incorporates the following tools for fast development and testing:

- **uv:** A modern, fast, and versatile Python package manager.
- **Pytest:** A flexible testing framework.
- **Ruff:** A powerful linter and code formatter.
- **GitHub Actions:** Automated linting and testing workflows.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Svaan1/python-template.git](https://github.com/Svaan1/python-template.git)
   cd python-template
   ```
2. **Install `uv`:**

   Windows:
   ```bash
   powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/installps1 | iex"
   ```

   MacOS and Linux
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh
   ```
   
3. **Run the application:**
   ```bash
   uv run src/main.py
   ```

## Making the Most of It

### Using `uv`

`uv` is a modern Python package manager that simplifies dependency management and environment setup, for more information on how to use uv while managing this project read: [Working with uv projects](https://docs.astral.sh/uv/guides/projects)


1. **Install Dependencies:**
   ```bash
   uv install
   ```

2. **Add a New Dependency:**
   ```bash
   uv add <package-name>
   ```

3. **Remove a Dependency:**
   ```bash
   uv remove <package-name>
   ```

### Using `Ruff`

`Ruff` is a powerful linter and code formatter that helps maintain code quality.

1. **Lint the Code:**
   ```bash
   uv run ruff check .
   ```

2. **Automatically Fix Issues:**
   ```bash
   uv run ruff fix .
   ```

### Using `Pytest`

`Pytest` is a flexible testing framework that makes it easy to write simple and scalable test cases.

1. **Run All Tests:**
   ```bash
   uv run pytest
   ```

2. **Run Specific Tests:**
   ```bash
   uv run pytest path/to/test_file.py
   ```

3. **Generate a Test Report:**
   ```bash
   uv run pytest --html=report.html
   ```