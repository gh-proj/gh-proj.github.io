# X Project Template

[![CI](https://github.com/x-pt/x-pt.github.io/actions/workflows/pages.yml/badge.svg)](https://github.com/x-pt/x-pt.github.io/actions)

A streamlined template for rapidly initializing and structuring projects on GitHub.

## Prerequisites

- Python 3.8 or higher
- cookiecutter

Install Cookiecutter:

```bash
uv tool install cookiecutter    # if no uv, follow this guide: https://docs.astral.sh/uv/
```

## Features

- Support for multiple programming languages:
    - CUDA
    - C++
    - Go
    - Python
    - Rust
    - TypeScript
- Pre-configured CI/CD pipeline
- Best practices for project structure
- Easy customization options

## Quick Start

Use the following commands to generate project templates:

```bash
# Generate a dynamic project template
cookiecutter gh:x-pt/template

# Generate language-specific templates
cookiecutter gh:x-pt/template --directory template/cuda  # CUDA
cookiecutter gh:x-pt/template --directory template/cxx   # C++
cookiecutter gh:x-pt/template --directory template/go    # Go
cookiecutter gh:x-pt/template --directory template/py    # Python
cookiecutter gh:x-pt/template --directory template/rs    # Rust
cookiecutter gh:x-pt/template --directory template/ts    # TypeScript
```

## Usage

1. Run one of the Quick Start commands above.
2. Follow the prompts to customize your project.
3. Navigate to your new project directory.
4. Start developing with a well-structured project template!

For more detailed information and advanced usage, please visit our [GitHub repository](https://github.com/x-pt).
