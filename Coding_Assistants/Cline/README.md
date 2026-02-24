# Cline — Prompt Guide

## Overview
Cline is an autonomous AI coding agent for VS Code. It can explore your project, write code, run terminal commands, browse docs, and debug — all while keeping you in the loop for approval.

## How to Use

### System Prompt
1. Paste `System_Prompt.txt` into Cline's custom instructions in VS Code settings.
2. This establishes the autonomous workflow pattern and human-in-the-loop protocol.

### User Prompts
- Use in Cline's chat panel within VS Code.
- Describe complete tasks — Cline will plan, execute, and iterate autonomously.
- Approve or modify Cline's proposed actions when prompted.

## Tips for Best Results
- **Give complete context** — describe the full task, constraints, and acceptance criteria.
- **Review plans** — check Cline's step-by-step plan before approving execution.
- **Provide feedback** — if Cline's approach isn't ideal, redirect it early.
- **Let it iterate** — Cline works best when it can write → test → fix cycles.
- **Use for complex tasks** — Cline shines on multi-step tasks that require terminal, editor, and browser.
