# Copilot Instructions for SWEN-HS25

This project consists of Jupyter notebooks for learning and practicing Python basics, control structures, data types, functions, clean code, classes, and unit testing (TDD). The workspace is organized for educational purposes, with each notebook focusing on a specific topic.

## Project Structure
- `01_Basics_und_Kontrolstrukturen.ipynb`: Python basics and control structures
- `02_Datentype_und_Funktionen.ipynb`: Data types and functions
- `03_Cleancode_und_Klassen.ipynb`: Clean code principles and classes
- `04_Unittesting_und_TDD.ipynb`: Unit testing and test-driven development
- `pyproject.toml`, `uv.lock`: Python environment and dependency management
- `README.md`: (currently empty)

## Developer Workflows
- **Environment Setup**: Use `pyproject.toml` and `uv.lock` for reproducible Python environments. Install dependencies with `uv` (e.g., `uv pip install -r requirements.txt` if requirements are present).
- **Notebook Execution**: Run and edit code directly in Jupyter notebooks. Each notebook is self-contained and demonstrates concepts with code and explanations.
- **Testing**: Unit tests and TDD examples are in `04_Unittesting_und_TDD.ipynb`. Follow the patterns shown for writing and running tests within notebooks.

## Conventions & Patterns
- All code and explanations are in German, matching the course language.
- Notebooks are named and ordered by topic and progression.
- Example code is concise and focused on illustrating concepts for students.
- No custom Python modules or package structure; all logic is in notebooks.
- Use standard Python libraries only unless otherwise specified in a notebook.

## Integration Points
- No external APIs or services are integrated.
- All dependencies should be managed via `pyproject.toml` and installed with `uv`.

## Tips for AI Agents
- When adding new content, follow the naming and topic conventions of existing notebooks.
- Keep code examples simple and educational.
- If updating environment or dependencies, modify `pyproject.toml` and regenerate `uv.lock`.
- For new tests, add them to the relevant notebook section, following the style in `04_Unittesting_und_TDD.ipynb`.

---
For questions or unclear conventions, ask for clarification or examples from the user.
