# AGENTS.md Collection for OpenAI Codex

This repository is a collection of AGENTS.md files for the OpenAI Codex, providing stack-specific guidelines to help ensure AI agents behave according to project conventions and best practices.

## What is AGENTS.md?

AGENTS.md is a software engineering guideline file, similar to the OpenAI Codex, for AI agents to function effectively within a project. It's the human developer equivalent of README.md, but specialized for AI agents.

## Available AGENTS.md files

### General purpose
- [`AGENTS.md`](./AGENTS.md) - General-purpose project templates

### front end
- [`nextjs-AGENTS.md`](./nextjs-AGENTS.md) - Next.js + TypeScript + Tailwind CSS
- [`react-AGENTS.md`](./react-AGENTS.md) - React + TypeScript + Vite
- [`vue-AGENTS.md`](./vue-AGENTS.md) - Vue.js 3 + Composition API + TypeScript

### Backend
- [`python-AGENTS.md`](./python-AGENTS.md) - Python + Flask + SQLAlchemy
- [`nodejs-AGENTS.md`](./nodejs-AGENTS.md) - Node.js + Express + TypeScript + Prisma

### Mobile
- [`flutter-AGENTS.md`](./flutter-AGENTS.md) - Flutter + Dart + Riverpod

## How to use

### 1. Copy the file to the project root

Select the appropriate AGENTS.md file and copy it to the root directory of your project as `AGENTS.md`.

```bash
# Example: Next.js project
cp agents-md/nextjs-AGENTS.md /path/to/your/project/AGENTS.md
```

### 2. Customize it for your project

Open the AGENTS.md file and adjust its contents to fit your project's specific requirements:

- Project-specific directory structure
- Specific libraries and tools used
- Team-specific coding standards
- Deployment instructions

### 3. Use in OpenAI Codex

When OpenAI Codex executes a task, it uses the AGENTS.md file as a guide to understand the context of the project and follow the appropriate guidelines.

## Main Sections of AGENTS.md

Each AGENTS.md file follows the following structure:

1. **Codebase Navigation and Architecture** - Understanding the project structure
2. **Code Style and Format** - Style guide and formatting rules
3. **Test Protocol** - Testing strategy and execution method
4. **Build Process and Environment Configuration** - Development and production environment configuration
5. **Commit Message Conventions** - Git commit message format
6. **Pull Request Instructions** - Guidelines for creating PRs
7. **General Project Guidelines** - Best practices and recommendations
8. **Review Checklist** - Review points for Codex-generated code

## Customization Tips

### Leveraging Scope

For large projects, you can place specialized AGENTS.md files in subdirectories:

```
project-root/
├── AGENTS.md              # For all
├── frontend/
│   └── AGENTS.md          # Front-end specialization
└── backend/
    └── AGENTS.md          # Backend specialization
```

### Gradual Implementation

We recommend starting with a basic AGENTS.md and gradually expanding it based on your team's experience.

### Regular Updates

As your project evolves, update your AGENTS.md to ensure your Codex adheres to the latest standards.

### Best Practices

1. **Clarity** - Avoid ambiguity and provide specific, actionable instructions.
2. **Concise** - Avoid verbose descriptions and get straight to the point.
3. **Actionability** - Provide commands and steps that can actually be executed.
4. **Consistency** - Maintain consistency in terminology and formatting within your project.
5. **Updating** - Regularly review the content and adapt it to changes in the project.

## Contributions

If you'd like to contribute an AGENTS.md file for a new tech stack or improve an existing one, please submit a pull request.

### License

The content of this repository is released under the [MIT License](./LICENCE).

## References

- [OpenAI Codex Documentation](https://openai.com/index/introducing-codex/)
- [Best Practices for AI Agent Guidelines](https://docs.anthropic.com/claude/docs/how-claude-works)
- [Effective Software Development with AI](https://www.temporal.io/blog/improving-java-sdk-codex-openai)
