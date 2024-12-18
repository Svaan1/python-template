# Python Template

My project template with tools and configurations i personally consider a must use in any of my python projects.

- **uv:** a fast and versatile package manager.
- **Pytest:** a testing framework.
- **Ruff:** for linting and code formatting.
- **GitHub Actions:** for automated workflows.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Svaan1/python-template.git
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

