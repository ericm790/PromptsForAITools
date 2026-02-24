# Claude Code — Prompt Guide

## Overview
Claude Code is Anthropic's AI pair programming assistant. These prompts are designed to extract maximum value from Claude Code for professional software development tasks.

## How to Use

### System Prompt
1. Copy the contents of `System_Prompt.txt`.
2. Paste it into Claude Code's system/custom instructions field (if configurable) or use it as a preamble in your conversations.
3. This sets the behavioral baseline — making Claude Code act as a senior engineer with strict quality standards.

### User Prompts
- Each prompt in `User_Prompts.txt` targets a common engineering scenario.
- **Adapt** them to your specific project — replace technology names, add your code snippets, and adjust constraints.
- **Be specific** — the more context you provide (stack, constraints, scale), the better the output.

## Tips for Best Results
- Always provide your **tech stack** and **project context** upfront.
- Include **code snippets** when asking for reviews, debugging, or refactoring.
- Ask Claude to **explain trade-offs** — it excels at reasoning through options.
- For complex features, break them into **smaller, sequential requests**.
- Request **tests alongside code** to get complete, production-ready deliverables.
