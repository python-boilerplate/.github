# Python Boilerplate

> A collection of modern Python project templates with pre-configured development tools, CI/CD pipelines, and best practices.

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub](https://img.shields.io/badge/GitHub-Organization-black)](https://github.com/python-boilerplate)

---

## Overview

**Python Boilerplate** is a curated collection of project templates designed to help developers quickly bootstrap new Python projects with industry best practices and modern tooling already configured.

### ✨ Why Use These Templates?

- **⚡ Fast Setup** - Get a production-ready project structure in seconds
- **🛠️ Modern Tooling** - Pre-configured linters, formatters, type checkers, and testing frameworks
- **🚀 CI/CD Ready** - Automated workflows for GitHub Actions
- **🐳 Docker Support** - Development and production containerization
- **📚 Documentation** - MkDocs integration with Material theme
- **🔧 Developer Experience** - Pre-commit hooks, Makefile automation, and dev containers

---

## Available Templates

### 🚀 UV Template
Modern Python project template using [uv](https://github.com/astral-sh/uv) - the ultra-fast Python package manager.

**[📂 uv-template](https://github.com/python-boilerplate/uv-template)** | **[📖 Documentation](https://python-boilerplate.github.io/uv-template/)**

**🎯 Core Features:**
- 🐍 **Python 3.10+** - Modern Python version support
- ⚡ **uv** - Ultra-fast Python project manager with dependency installer and lock file support
- 🐳 **Docker Support** - Multi-stage Dockerfiles for easy local development and clean production containers
- 🔄 **GitHub Actions CI/CD** - Automated linting, testing, static analysis, and security checks for every branch
- 💻 **Dev Containers** - Ready-to-use development environment in GitHub Codespaces or VSCode Remote Containers

**🛠️ Code Quality Tools:**
- 🔍 **Ruff** - Built-in linting and formatting
- 🔎 **MyPy** - Static type checking
- 🧪 **Pytest** - Testing framework with async support
- 📊 **Vermin** - Minimum Python version analysis

**⚙️ Developer Experience:**
- 🎣 **Pre-commit Hooks** - Runs linters, formatting, and tests automatically before every commit
- 📝 **Commitizen** - Standardized commit messages with automated versioning and changelog updates
- 🌍 **Environment Management** - Stage-based environment variable configuration for dev/prod with switching via `APP_STAGE`
- 📖 **MkDocs Documentation** - Project documentation generated with MkDocs and the Material theme
- 🔧 **Makefile Automation** - Common tasks available as simple Makefile commands

### 📦 Poetry Template
Classic Python project template using [Poetry](https://python-poetry.org/) for dependency management.

**[📂 poetry-template](https://github.com/python-boilerplate/poetry-template)** | **[📖 Documentation](https://python-boilerplate.github.io/poetry-template/)**

**🎯 Core Features:**
- 🐍 **Python 3.10+** - Modern Python version support
- 📦 **Poetry** - Mature dependency management with lock files
- 🐳 **Docker Support** - Containerization for development and production
- 🔄 **CI/CD Pipelines** - Automated quality checks and deployment workflows
- 📚 **Structured Documentation** - Well-organized project documentation

---

## Quick Start

1. **Choose your template** from the list above
2. **Use as GitHub Template** - Click "Use this template" button on the repository page
3. **Clone your new repository**
   ```bash
   git clone https://github.com/your-username/your-project-name.git
   cd your-project-name
   ```
4. **Initialize the project**
   ```bash
   make init
   ```
5. **Start developing!** 🎉

---

## Templates Comparison

| Feature | UV Template | Poetry Template |
|---------|-------------|-----------------|
| Package Manager | uv (ultra-fast) | Poetry (mature) |
| Dependency Locking | ✅ uv.lock | ✅ poetry.lock |
| Python Version Management | ✅ Built-in | ❌ External tool needed |
| Speed | ⚡ Fastest | 🐌 Slower |
| Ecosystem Maturity | 🆕 New but growing | 🏆 Well-established |
| Learning Curve | 📈 Minimal | 📊 Moderate |

---

## Documentation

- **[GitHub Organization](https://github.com/python-boilerplate)** - All templates and repositories
- **[UV Template Docs](https://python-boilerplate.github.io/uv-template/)** - Complete uv template documentation
- **[Poetry Template Docs](https://python-boilerplate.github.io/poetry-template/)** - Complete poetry template documentation

---

## Contributing

We welcome contributions! If you have ideas for improvements or new templates:

1. **Open an issue** to discuss your idea
2. **Fork the repository** and make your changes
3. **Submit a pull request** with a clear description

---

## Support

- 📋 **Issues** - Report bugs or request features in the specific template repository
- 💬 **Discussions** - Ask questions in GitHub Discussions
- 📧 **Contact** - Reach out to [@monok8i](https://github.com/monok8i)

---

## License

All templates are released under the [MIT License](LICENSE).

---

<div align="center">

**Made with ❤️ by the [Python Boilerplate](https://github.com/python-boilerplate) team**

[⭐ Follow the Organization](https://github.com/python-boilerplate) • [📋 Browse Templates](https://github.com/orgs/python-boilerplate/repositories) • [💬 Join Discussions](https://github.com/orgs/python-boilerplate/discussions)

</div>
