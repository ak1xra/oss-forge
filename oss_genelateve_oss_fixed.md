# OSS Forge: OSSを生成するOSS

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  <img src="https://img.shields.io/badge/status-MVP-green.svg" />
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" />
</p>

## Overview

OSS Forge is an "OSS that generates OSS". It's not just a template distribution, but a "meta-build system" that transforms requirements into **structured → standardized → skeleton generation**.

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
git clone https://github.com/[username]/oss-forge.git
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

---

## LICENSE

```text
MIT License

Copyright (c) 2025 AK1RA

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## CONTRIBUTING.md

# Contributing Guide

We welcome contributions to OSS Forge. Here's how you can participate:

## Issues

- Bug reports and improvement requests should be submitted to [Issues](../../issues)

## Pull Requests

- Create PRs for new templates and improvement proposals
- Run lint/format checks before submitting PRs

## Development Rules

- Use schema (`scaffold.schema.json`) as the single source of truth
- PRs must pass schema consistency CI checks

## Code of Conduct

- Please follow [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) at all times

## SECURITY.md

# Security Policy

## Code Usage Guidelines

- Generated code must be manually reviewed
- Automatic detection of sensitive information is recommended
- Always run vulnerability scans on dependencies

## Reporting

If you discover a security vulnerability, please report it via [Issues](../../issues).

## CODE_OF_CONDUCT.md

# Code of Conduct

## Basic Principles

- Respect others
- No defamation or slander
- Welcome technical discussions, prohibit personal attacks

## Compliance

All participants in this project must follow this Code of Conduct.

## Violation Response

- Minor violations: Warning
- Severe violations: Exclusion from project

## requirements.txt

```text
# Requirements for OSS Forge
# This is lightweight: only for demo scaffold

pyyaml>=6.0
jsonschema>=4.17.0
```

---

This is the latest version with integrated consistency.
👉 Ready for Claude Code review and final checks.

The badges (MIT / MVP) and "ready to use" emphasis are included before review.
Proceed?
