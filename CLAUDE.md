# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is **Adams Vibe Coding Template** - a comprehensive AI-assisted development framework that provides structured rules and workflows for consistent AI collaboration. The project implements a three-phase development methodology: PRD creation, task generation, and iterative task processing.

## Core Architecture

### Rule System Structure
- **adams-rules/**: MDC (Markdown Configuration) files for AI assistant behavior
- **ai-dev-tasks/**: Structured workflow templates for feature development  
- **ai-notes/**: Knowledge management and documentation storage

### Key Components
- **Environment Management**: Virtual environments preferred over global installations
- **Documentation-First Approach**: Automatic README updates and living documentation
- **Task Orchestration**: Three-phase development workflow with user confirmation gates
- **Template System**: Consistent formatting using README-template.md patterns

## Development Workflows

### AI-Assisted Feature Development
1. **PRD Creation**: Use `ai-dev-tasks/create-prd.mdc` to define feature scope
2. **Task Generation**: Apply `ai-dev-tasks/generate-tasks.mdc` to break down PRD
3. **Task Processing**: Execute with `ai-dev-tasks/process-task-list.mdc` (one sub-task at a time)

### Task Management Protocol
- Process tasks incrementally with user confirmation between sub-tasks
- Mark completed tasks with `[x]` immediately upon completion
- Maintain "Relevant Files" tracking in task lists
- Update README.md after every completed task

### Documentation Standards
- Target **junior developers** - provide clear, actionable guidance
- Use structured file naming: `api-[service].md`, `workflow-[process].md`
- Documentation must be: actionable, current, discoverable, and concise
- Create ai-notes for significant discoveries or implementations

## Rule File Integration

### Always-Applied Rules
- **environment-rule.mdc**: Virtual environment enforcement
- **readme-rule.mdc**: README maintenance standards
- **misc-rules.mdc**: Contextual information (dates, etc.)

### Workflow-Specific Rules  
- **ai-dev-tasks-rule.mdc**: Development task orchestration
- **notes-rule.mdc**: Knowledge management conventions

### Rule Application Pattern
Reference specific MDC files using `@filename.mdc` syntax when relevant to the task context.

## File Organization Principles

### Project Structure
```
adams-vibe-coding-template/
   adams-rules/           # Core AI behavior rules
   ai-dev-tasks/         # Development workflow templates
      tasks/           # Active project task directories
      *.mdc           # Workflow command files
   ai-notes/            # Project knowledge base
```

### Quality Standards
- **Modularity**: Each rule addresses specific concerns
- **Maintainability**: Self-updating documentation systems
- **AI-Friendly**: Clear decision points and structured outputs
- **Scalability**: Support for multiple concurrent projects

## Critical Context

### Business Logic
This template standardizes AI-assisted development patterns, ensuring reproducible workflows across different projects and team members. The system emphasizes structured iteration over monolithic AI requests.

### Development Philosophy
- **Incremental Progress**: One task at a time with verification gates
- **Documentation-Driven**: Every change updates relevant documentation
- **Template Consistency**: Use established patterns from rule files
- **Quality Assurance**: Junior developer accessibility standard

### Integration Points
- Git workflows with conventional commit patterns
- Testing frameworks (primarily Jest-based patterns)
- Markdown-based knowledge management
- Task tracking and completion protocols

## Working with This Repository

### For Template Customization
1. Modify rule files in `adams-rules/` to match project needs
2. Adapt workflow templates in `ai-dev-tasks/` for specific use cases
3. Maintain the three-phase development structure for consistency

### For AI Assistant Configuration
- Reference relevant MDC files when establishing AI behavior
- Follow the established workflow patterns for feature development
- Maintain documentation standards throughout development cycles

### License Compliance
This project includes Apache 2.0 licensed components in `ai-dev-tasks/`. When redistributing, maintain:
- `NOTICE` file with full attribution
- Both license files (`LICENSE` and `ai-dev-tasks/LICENSE`)
- Required modification notices per Apache License 2.0