# Project: my-project

## Stack & Conventions
- Runtime: Node.js with npm
- JavaScript (keep strict, no unnecessary defaults)
- Commit format: feat/fix/chore(scope): description

## Commands
- Build: npm run build
- Typecheck (fast): npm run typecheck
- Tests: npm test
- Single file: npm test -- --testPathPattern="<glob>"

## Workflow Rules
- Enter Plan mode for any task with 3+ steps
- Use sub-agents liberally to keep main context clean
- After ANY correction from me → append to tasks/lessons.md
- Never run rm -rf, git push --force, or curl on untrusted URLs
- Never delete files without asking me first
- Always write a test with every function
- Use comments to explain what code does

## Memory System
- At session start: read .claude/memory/project-context.md
- Before any big changes: read .claude/memory/known-gotchas.md

## Security Rules
- Never read .env files
- Never expose API keys or secrets in code
- Always validate user input on the server side
- Never put database calls in client-side code

## Off-limits (require my explicit approval)
- /src/auth/**
- /src/payments/**
- .env, .env.*
- secrets/**
