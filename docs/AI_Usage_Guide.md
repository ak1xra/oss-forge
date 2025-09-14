# AI Usage Guide for OSS Forge

## Purpose
This guide explains how to use **OSS Forge** with modern AI coding assistants.  
It is designed for both engineers and non-engineers who want to quickly scaffold an OSS project.

> ⚠️ **Note**: Currently, `forge_codex.md` is a placeholder (empty).  
> This guide shows the **planned usage** for the next phase of OSS Forge.

---

## Prerequisites
- GitHub account
- Installed Python 3.8+
- Compatible AI tools:
  - Cursor
  - Claude Code
  - Codex

---

## Step 1: Clone the Repository
```bash
git clone https://github.com/ak1xra/oss-forge.git
cd oss-forge
```

## Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

## Step 3: Open Your AI Tool
- **Cursor**: Open the repo folder, highlight `forge_codex.md`, and run with context
- **Claude Code**: Upload `forge_codex.md` into your chat and ask Claude to generate the project
- **Codex**: Provide `forge_codex.md` as the input file

## Step 4: Generate a Project

Ask your AI tool:
> Use forge_codex.md as context. Generate an OSS skeleton project (README + LICENSE + dirs + sample code).

## Step 5: Verify Output
- Check that the following files exist:
  - README.md
  - LICENSE
  - Directory structure
  - Minimal template code
- Run basic lint/tests if included

---

## FAQ

**Q1. Do I need to be an engineer to use this?**  
No. The system is designed to let anyone scaffold an OSS repo in minutes.

**Q2. What if the AI output fails?**  
Just re-run with the same context. Use the self-check prompt (planned feature).

**Q3. Is this production-ready code?**  
No. The generated code is a starting point. Always review and extend before release.

---

## Best Practices
- Keep `forge_codex.md` small and focused for best AI results
- Start with one language template, then extend
- Always review generated code before publishing