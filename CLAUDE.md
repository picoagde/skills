# claude.md — Claude-specific skill notes

## Overview

This file documents how to use **Claude** (the Claude model) through the skills system in this repository.

## Usage

1. Place your Claude prompts or tasks in a markdown file under `skills/claude/` (e.g., `intro.md`, `prompt-templates.md`).
2. Reference the skill by its path, e.g.:

   ```markdown
   ## Skill: claude.md
   - **Model**: Claude
   - **Prompt template**: see `prompts/...`
   ```

3. When invoking a Claude task, point to this file so the system knows which model and prompt conventions to apply.
