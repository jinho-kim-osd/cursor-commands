# Cursor AI Custom Commands

A collection of custom commands for enhancing productivity with Cursor AI. This repository contains carefully crafted prompts and system instructions for various development tasks.

## Overview

This repository serves as a centralized location for Cursor AI custom commands, making it easier to maintain and share commonly used development workflows.

## Commands

### INPUT

Note: This section ends with "# INPUT" because you should append your diff content using @Commit(Diff of Working State) tag after this marker when using the command.

Example usage:

```git
@create-commit @Commit (Diff of Working State)
```

### Available Commands

- `@create-commit` - Generates standardized commit messages following Conventional Commits format([1](https://github.com/dgokcin/dotfiles/blob/main/ai-stuff/cursor/prompts/create-commit/system.md))

### Command Structure

Each command is stored in the `/commands` directory with the following structure:
