# Cursor — Prompt Guide

## Overview
Cursor is an AI-first code editor that understands your entire codebase. These prompts are designed to leverage Cursor's unique capabilities: codebase indexing, multi-file editing, and inline AI assistance.

## How to Use

### System Prompt
1. Copy the contents of `System_Prompt.txt`.
2. Paste into Cursor's **Rules for AI** section (Settings → General → Rules for AI) or into a `.cursorrules` file at your project root.

### User Prompts
- Use prompts in Cursor's **Chat panel** (Cmd/Ctrl + L) or **Inline Edit** (Cmd/Ctrl + K).
- Leverage `@` mentions: `@codebase`, `@file`, `@folder`, `@symbol` to give Cursor precise context.

## Tips for Best Results
- **Use `@codebase`** for project-wide questions and cross-file changes.
- **Use `@file`** to point Cursor at specific files when you need targeted edits.
- **Select code first** and press Cmd/Ctrl+K for inline edits on selected regions.
- **Paste terminal errors** directly into chat — Cursor can parse stack traces.
- **Create `.cursorrules`** files for project-specific instructions that persist.
