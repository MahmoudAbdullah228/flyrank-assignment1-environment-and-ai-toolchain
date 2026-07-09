# FlyRank AI Internship - Assignment 1: Environment & AI Toolchain

**Phase:** Setup · **Estimated hours:** 3  
**Repository:** [flyrank-assignment1-environment-and-ai-toolchain](https://github.com/MahmoudAbdullah228/flyrank-assignment1-environment-and-ai-toolchain)

---

## Project Overview & Objective

AI-assisted development is the core skill of the Frontend AI Engineer track at FlyRank. Before building features, this assignment establishes a reliable local environment and a documented AI toolchain so every future task can be executed with consistent tooling, conventions, and version control.

### Why it matters

Professional AI-assisted engineering is not only about prompting models — it requires a reproducible setup: the right runtime, editor, Git workflow, and project conventions that both the developer and the AI assistant can follow. This assignment proves that foundation is in place.

### Assignment brief

| Step | Requirement |
|------|-------------|
| 1 | Install **Node.js (LTS)**, **Git**, and your editor |
| 2 | Set up **Claude Code** in the terminal or **Cursor** as your IDE |
| 3 | Create the capstone GitHub repo with **README stub**, **license**, **`.gitignore`**, and **`CLAUDE.md`** (or Cursor rules file) describing stack and conventions |
| 4 | Make the **first three commits** using **Conventional Commits** format — final Git history is evaluated |
| 5 | Ask your AI assistant to **critique the README** and apply **one improvement** |
| 6 | Submit the **repo URL** plus a **screenshot** of your AI assistant completing a task in your environment |

**Deliverable:** Repository URL + screenshot showing Claude Code or Cursor working in the local environment.

---

## System & Environment Specifications

### Hardware

| Component | Specification |
|-----------|---------------|
| **Machine** | Lenovo ThinkPad P50 |
| **Processor** | Intel Core i7-6700HQ |
| **Graphics** | Nvidia Quadro M1000M |
| **Memory** | 16 GB DDR4 RAM |
| **Storage** | 512 GB SSD |

### Software & toolchain

| Tool | Version / selection | Purpose |
|------|---------------------|---------|
| **Operating System** | Windows 10/11 | Local development environment |
| **Node.js** | LTS | JavaScript runtime for upcoming frontend assignments |
| **Git** | Latest stable | Version control and Conventional Commits workflow |
| **IDE & AI assistant** | **Cursor IDE** | Primary editor and AI-assisted development toolchain |
| **Remote hosting** | GitHub | Capstone repository and internship deliverables |

### Local setup commands

```bash
# Verify toolchain
node --version
git --version

# Clone this repository
git clone https://github.com/MahmoudAbdullah228/flyrank-assignment1-environment-and-ai-toolchain.git
cd flyrank-assignment1-environment-and-ai-toolchain
```

### AI toolchain choice

**Cursor IDE** is used as the primary AI-assisted development environment for this assignment. The workspace is opened at the repository root so the agent can read project files, apply focused edits, and support the README critique task required by the brief.

---

## Deliverables & Verification Checklist

Use this checklist to confirm the assignment meets FlyRank evaluation criteria before submission.

| Deliverable | Requirement | Status |
|-------------|-------------|--------|
| `README.md` | Project documentation for Assignment 1 | ☑ |
| `LICENSE` | License file included in repository | ☑ |
| `.gitignore` | Ignores environment and dependency artifacts | ☑ |
| `CLAUDE.md` or Cursor rules | Documents stack, conventions, and AI workflow | ☑ |
| **Conventional Commits** | At least three commits in valid format | ☑ |
| **AI toolchain screenshot** | Shows Cursor or Claude Code completing a task locally | ☐ |
| **Repository URL** | Public GitHub link submitted with deliverable | ☑ |

### Expected repository structure

```
flyrank-assignment1-environment-and-ai-toolchain/
├── README.md          # Assignment documentation (this file)
├── LICENSE            # Project license
├── .gitignore         # Ignored files and folders
├── CLAUDE.md          # Stack and conventions (or .cursor/rules/)
└── ...
```

### Evaluation criteria (from brief)

- Repo has **README**, **license**, and a **`CLAUDE.md` or rules file**
- At least **three commits** in **Conventional Commits** format
- **Screenshot** shows **Claude Code** or **Cursor** working

---

## Git History & Commit Conventions

All commits for this assignment follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>(<optional scope>): <short description>
```

### Commit types used in Assignment 1

| Type | Use in this assignment |
|------|------------------------|
| `chore` | Initial repo scaffold — license, `.gitignore`, project conventions file |
| `docs` | README stub, README improvements, documentation updates |
| `feat` | Reserved for future feature work beyond this setup phase |

### First three commits — intended structure

| # | Example commit message | What it documents |
|---|------------------------|-------------------|
| 1 | `chore: initialize repository with license and gitignore` | Base repo files and version-control setup |
| 2 | `docs: add README stub and AI toolchain conventions file` | `README.md` stub plus `CLAUDE.md` or Cursor rules |
| 3 | `docs: apply AI-assisted README improvement` | README critique task completed in Cursor |

### Examples

```bash
git commit -m "chore: initialize repository with license and gitignore"
git commit -m "docs: add README stub and CLAUDE.md conventions"
git commit -m "docs: apply AI-assisted README improvement"
```

> **Note:** Take a screenshot of Cursor completing a task (e.g. this README rewrite) and attach it to your assignment submission.

---

## Repository Link

**Official repository:**  
https://github.com/MahmoudAbdullah228/flyrank-assignment1-environment-and-ai-toolchain

---

## Author

**Mahmoud Abdullah**  
Frontend AI Engineer Intern — FlyRank AI
