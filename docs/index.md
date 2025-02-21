# Zenith Project Documentation

Welcome to the **Zenith** project!

Zenith is a simple Python application template designed to be modular, easy to maintain, and highly customizable. This project includes a CLI interface, a basic application module, and unit tests.

---

## Project Structure

```text
├── Containerfile            # Container build instructions
├── CONTRIBUTING.md          # Guidelines for contributors
├── docs                     # Documentation site
│   └── index.md             # This documentation file
├── .gitignore               # Files to ignore in Git
├── HISTORY.md               # List of changes in the project
├── LICENSE                  # License for the project
├── Makefile                 # Utility tasks (install, test, docs, etc.)
├── MANIFEST.in              # Files to include in the package
├── mkdocs.yml               # MkDocs configuration for docs site
├── zenith                   # Main Python package
│   ├── __init__.py          # Package initialization
│   ├── __main__.py          # Entry point for the project
│   ├── base.py              # Contains core logic (greeting function)
│   └── cli.py               # Command Line Interface (calls base functions)
├── README.md                # Project overview and instructions
├── setup.py                 # Packaging and installation script
├── requirements.txt         # Runtime dependencies (currently empty)
├── requirements-test.txt    # Dependencies for testing and development
└── tests                    # Unit tests for the project
    └── test_base.py         # Tests for the core functionality
```
