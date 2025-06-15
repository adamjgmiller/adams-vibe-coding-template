# Adams Vibe Coding Template

A comprehensive AI-assisted coding template project featuring structured rules and development workflows.

## Project Identity & Purpose

This project provides a structured template for AI-assisted software development using tools like Cursor, Claude Code, and other AI coding assistants. It establishes consistent rules and workflows for maintaining high-quality, well-documented code.

**Core Value:** Standardizes AI collaboration patterns and coding practices for improved developer productivity and code quality.

**Current Status:** Template/Framework - Ready for use and customization

## Quick Start (< 5 minutes)

### Prerequisites
- Git installed
- An AI coding assistant (Cursor, Claude Code, etc.)
- Text editor or IDE

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd adams-vibe-coding-template
   ```

2. Copy the relevant rule files to your AI coding tool:
   - For Cursor: Rules are in `adams-rules/` directory
   - For Claude Code: Reference the `.mdc` files as needed
   - For other tools: Adapt the rule files accordingly

3. Customize the rules in `adams-rules/` to match your project needs

### First Successful Run
After setup, your AI assistant should be able to reference the established rules and workflows defined in the project.

## Architecture Overview

### Tech Stack
- **Rule Definition**: Markdown (.mdc) files for AI tool configuration
- **Workflow Management**: Structured task definitions in `ai-dev-tasks/`
- **Documentation**: Self-maintaining README and rule documentation

### Key Components
- `adams-rules/`: Core rule definitions for AI assistants
  - `readme-rule.mdc`: README maintenance standards
  - `environment-rule.mdc`: Environment setup guidelines  
  - `notes-rule.mdc`: Note-taking conventions
  - `ai-dev-tasks-rule.mdc`: AI development task management

- `ai-dev-tasks/`: Development workflow definitions
  - Task templates and processing guidelines

### System Architecture
```
adams-vibe-coding-template/
├── adams-rules/           # AI assistant rule definitions
├── ai-dev-tasks/         # Development workflow templates
├── .gitignore           # Git ignore patterns
└── README.md            # Project documentation
```

## Development Workflow

### Local Development Setup
1. Initialize your preferred AI coding assistant with the project rules
2. Reference the appropriate `.mdc` files for coding standards
3. Follow the task templates in `ai-dev-tasks/` for consistent workflows

### AI Collaboration Guidelines
- **Primary Rules Reference**: All `.mdc` files in `adams-rules/` directory
- **Effective Prompts**: Reference specific rule files when requesting AI assistance
- **Code Style**: Follow patterns established in the rule files
- **AI Capabilities**: Rules are designed for tools like Cursor, Claude Code, Windsurf, etc.

### Git Workflow
- Use descriptive commit messages
- Follow conventional commit patterns when possible
- Keep rule files updated as the project evolves

## Critical Context

### Business Logic
This template establishes consistent patterns for AI-assisted development, ensuring reproducible and maintainable code across different projects and team members.

### Security Considerations
- Rule files contain no sensitive information
- Template is designed for safe sharing and collaboration
- Follow your organization's security guidelines when adapting rules

### Known Limitations
- Rules may need customization for specific project types
- Some AI tools may interpret rules differently
- Regular updates may be needed as AI tools evolve

## Team Knowledge

### Rule File Ownership
- `readme-rule.mdc`: Establishes documentation standards
- `environment-rule.mdc`: Defines environment setup patterns
- `notes-rule.mdc`: Note-taking and documentation conventions
- `ai-dev-tasks-rule.mdc`: Task management workflows

### Decision Rationale
- Chose `.mdc` format for maximum compatibility across AI tools
- Structured rules to be both human-readable and AI-parseable
- Focused on practical, actionable guidelines rather than abstract principles

### Troubleshooting
- If AI assistant isn't following rules: Check rule file syntax and references
- For rule conflicts: Higher-numbered rule files take precedence
- For tool-specific issues: Refer to your AI tool's documentation on rule file support

---

**Last Updated:** June 15, 2025

## License & Compliance

This project contains components under different licenses:

**Main Project:** Available under a permissive open-source license for educational and development purposes.

**⚠️ Apache Licensed Components:** The `ai-dev-tasks/` directory contains modified files originally licensed under Apache License 2.0.

**IMPORTANT COMPLIANCE NOTICE:** This project includes modified Apache 2.0 licensed content. When redistributing this project, you must:
- Retain the `NOTICE` file with full attribution
- Include both license files (`LICENSE` and `ai-dev-tasks/LICENSE`)
- Maintain modification notices as required by Apache License 2.0

**License Files:**
- `LICENSE` - Main project license  
- `ai-dev-tasks/LICENSE` - Apache License 2.0 for components
- `NOTICE` - Required attribution and modification notices

Adapt and modify as needed for your specific use case, while maintaining proper attribution.