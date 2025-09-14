# OSS Forge: OSS that generates OSS

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  <img src="https://img.shields.io/badge/status-MVP-green.svg" />
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" />
</p>

## Overview

OSS Forge is an "OSS that generates OSS". It's not just a template distribution, but a **meta-build system** that transforms requirements into **structured → standardized → skeleton generation**.

Generate the following with minimal input:
- README.md
- LICENSE
- Directory structure
- Template code (+ minimal tests)

## Background

The initial phase of OSS development (requirements definition → initial commit) tends to be personal and time-consuming. Forge automates this "logistics" and dramatically improves initial velocity, consistency, and reproducibility.

## System Requirements

- Python 3.8+
- Compatible AI tools: Cursor / Claude Code / Codex
- Output formats: Markdown, JSON, language-specific templates

## Quick Start

```bash
git clone https://github.com/ak1xra/oss-forge.git
cd oss-forge
pip install -r requirements.txt
python forge.py --help
```

## Usage Example

1. Clone this repository
2. Open Cursor / Claude Code / Codex
3. Provide `forge_codex.md` as context
4. Instantly receive a generated OSS skeleton (README + LICENSE + dirs + sample code)
5. Push the result back to your own repository

**Ready to use**: No additional setup required. Just load it into a compatible AI tool and your initial commit is ready.

## Features

- **Structured Requirements**: Convert natural language requirements into structured schemas
- **Template Generation**: Generate boilerplate code for multiple languages
- **Consistency**: Ensure consistent project structure across different OSS projects
- **AI Integration**: Optimized for modern AI coding assistants

## Project Structure

```
oss-forge/
├── forge.py              # Main generation script
├── templates/            # Language-specific templates
├── schemas/              # JSON schemas for validation
├── examples/             # Example outputs
└── docs/                 # Documentation
```

## Contributing

- **Issues**: Bug reports and feature requests
- **Pull Requests**: Template additions and improvements
- **Code of Conduct**: See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

## Security

- Generated code must be manually reviewed
- Automatic detection of sensitive information is recommended
- Vulnerability scanning of dependencies is recommended

## License

MIT License. See [LICENSE](LICENSE) for details.

## Strong Message

This is not template distribution. It's a "Forge" that crafts OSS skeletons from requirements.