# Homebrew Formula: onenote-to-obsidian

Homebrew formula for [onenote-to-obsidian](https://github.com/Lenivvenil/onenote-to-obsidian) — a CLI tool to export Microsoft OneNote notebooks to Obsidian-compatible Markdown via Microsoft Graph API.

[![PyPI Version](https://img.shields.io/pypi/v/onenote-to-obsidian.svg)](https://pypi.org/project/onenote-to-obsidian/)

## Installation

```bash
brew install Lenivvenil/onenote-to-obsidian/onenote-to-obsidian
```

Or add the tap first:

```bash
brew tap Lenivvenil/onenote-to-obsidian
brew install onenote-to-obsidian
```

### Install from HEAD (latest development version)

```bash
brew install --HEAD Lenivvenil/onenote-to-obsidian/onenote-to-obsidian
```

## Usage

```bash
# Export all notebooks
onenote-to-obsidian

# List available notebooks
onenote-to-obsidian --list

# Export a specific notebook
onenote-to-obsidian --notebook "My Notebook"

# Show help
onenote-to-obsidian --help
```

## Updating

```bash
brew update
brew upgrade onenote-to-obsidian
```

## Alternative installation methods

| Method | Command |
|--------|---------|
| **Homebrew** | `brew install Lenivvenil/onenote-to-obsidian/onenote-to-obsidian` |
| **pip** | `pip install onenote-to-obsidian` |
| **Docker** | `docker pull ghcr.io/lenivvenil/onenote-to-obsidian` |
| **From source** | `pip install -e .` |

## Links

- [Project Repository](https://github.com/Lenivvenil/onenote-to-obsidian)
- [Documentation](https://lenivvenil.github.io/onenote-to-obsidian/)
- [PyPI](https://pypi.org/project/onenote-to-obsidian/)
- [Changelog](https://github.com/Lenivvenil/onenote-to-obsidian/releases)
