# CLAUDE.md — FlyRank AI Internship Conventions

This file describes the stack, workflow, and coding conventions for the **Frontend AI Engineer** track. It is read by AI assistants (Claude Code, Cursor Agent) to keep contributions consistent across assignments.

## Project context

- **Intern:** Mahmoud Abdullah
- **Track:** Frontend AI Engineer — FlyRank AI Internship
- **Current phase:** Assignment 1 — Environment & AI Toolchain
- **Repository:** https://github.com/MahmoudAbdullah228/flyrank-assignment1-environment-and-ai-toolchain

## Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js (LTS) |
| Version control | Git + GitHub |
| IDE & AI toolchain | Cursor IDE |
| OS | Windows 10/11 (ThinkPad P50) |

Upcoming frontend assignments will extend this stack (framework, styling, testing). Until then, focus on documentation, tooling, and clean Git history.

## AI-assisted development rules

1. **Scope changes narrowly** — one task, one logical commit; avoid unrelated edits.
2. **Read before writing** — inspect existing files and match naming, structure, and tone.
3. **Review all AI diffs** — treat generated output as a draft; verify before committing.
4. **No secrets in Git** — never commit `.env`, API keys, tokens, or credentials.
5. **Prefer minimal diffs** — smallest correct change over large rewrites.
6. **Use `@` file references in Cursor** — give the agent precise file context instead of pasting large blocks.

## Git conventions

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>(<optional scope>): <short description>
```

| Type | When to use |
|------|-------------|
| `feat` | New feature |
| `fix` | Bug fix |
| `docs` | README, CLAUDE.md, comments |
| `chore` | Tooling, config, `.gitignore`, license |
| `refactor` | Code change without feature or fix |

Examples:

```bash
git commit -m "chore: initialize repository with license and gitignore"
git commit -m "docs: add README stub and CLAUDE.md conventions"
git commit -m "docs: apply AI-assisted README improvement"
```

## Code style (for upcoming assignments)

- Use clear, descriptive file and variable names.
- Keep components and functions small and single-purpose.
- Add comments only for non-obvious business logic.
- Run lint/build commands after substantive code changes.

## Assignment 1 deliverables

- [x] README.md
- [x] LICENSE
- [x] .gitignore
- [x] CLAUDE.md (this file)
- [x] Three Conventional Commits
- [ ] Screenshot of Cursor completing a task (submit separately)

## Contact

**Mahmoud Abdullah** — Frontend AI Engineer Intern, FlyRank AI
