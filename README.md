# Building with the Anthropic API — Prep Course

My exercises and notes from the **Building with the Anthropic API** course, completed as preparation for the Anthropic architect foundations certificate.

## Purpose

- Work through each course exercise hands-on.
- Keep the code and notes together as a study reference for the certificate.

## Layout

Each course section has its own folder, numbered in course order. A section folder holds everything for that section: my own exercise notebooks, the notebooks downloaded from the course, and any files they read or write (datasets, eval reports).

| Folder | Course section | Status |
| --- | --- | --- |
| `01_accessing_claude_with_the_api/` | Accessing Claude with the API | Done |
| `02_prompt_evaluation/` | Prompt evaluation | Done |
| `03_prompt_engineering_techniques/` | Prompt engineering techniques | In progress |
| `04_tool_use_with_claude/` | Tool use with Claude | Not started |
| `05_rag_and_agentic_search/` | RAG and agentic search | Not started |
| `06_features_of_claude/` | Features of Claude | Not started |
| `07_model_context_protocol/` | Model Context Protocol | Not started |
| `08_anthropic_apps_claude_code_and_computer_use/` | Anthropic apps — Claude Code and computer use | Not started |
| `09_agents_and_workflows/` | Agents and workflows | Not started |

Notebooks keep the course's numbering (`001_`, `002_`, …), which restarts in every section.

## Setup

The `.env` file (API key) and the `.venv` virtual environment stay at the repository root and are shared by all sections. `load_dotenv()` searches parent folders, so notebooks in a section folder find the root `.env` without changes.
