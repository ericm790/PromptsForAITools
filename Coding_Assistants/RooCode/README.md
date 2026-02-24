# RooCode — Prompt Guide

## Overview
RooCode is an AI coding assistant with multiple specialized modes (Code, Architect, Debug, Review, Document) for different development tasks.

## How to Use

### System Prompt
1. Use `System_Prompt.txt` in RooCode's custom instructions.
2. This activates multi-mode operation and quality standards.

### User Prompts
- **Always specify the mode** at the start: "Switch to [Code/Architect/Debug/Review/Document] mode."
- Each mode optimizes RooCode's behavior for that specific task type.

## Tips for Best Results
- **Use the right mode** — don't use Code mode for architecture questions.
- **Provide full context** — include tech stack, constraints, and existing patterns.
- **Chain modes** — start with Architect mode to plan, then Code mode to implement.
- **Use Review mode** for PRs and refactoring decisions.
- **Use Document mode** to generate docs for existing code.
