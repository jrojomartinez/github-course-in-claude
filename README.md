# Git & GitHub Interactive Course

An interactive, hands-on course on Git and GitHub delivered through Claude Code slash commands. Claude acts as your personal tutor, guiding you through concepts, real exercises in a playground repository, and understanding checks.

## Prerequisites

- [Claude Code](https://claude.com/claude-code) installed
- A GitHub account
- `git` installed (`git --version` to verify)
- `gh` CLI installed (`brew install gh` on Mac, then `gh auth login`)

## Modules

**Total estimated time: ~6-8 hours** (excluding optional Module 11)

| # | Module | Est. Time | Description |
|---|--------|-----------|-------------|
| 0 | Course Setup | ~20 min | Create your playground repo, verify tools, learn git vs gh |
| 1 | Why Version Control? | ~25 min | The problem git solves — snapshots and timelines |
| 2 | Repos & Commits | ~30 min | The three areas (working dir, staging, history) and what a commit really is |
| 3 | Branches | ~30 min | Parallel timelines — pointers, HEAD, and why branches are cheap |
| 4 | Merging & Conflicts | ~40 min | Fast-forwards, merge commits, and resolving conflicts |
| 5 | Remotes & GitHub | ~40 min | Push, pull, fetch — the local/remote relationship |
| 6 | Pull Requests & Code Review | ~45 min | PRs, review workflows, and merge strategies |
| 7 | Collaboration Workflows | ~35 min | Feature branch, trunk-based, gitflow, and fork workflows |
| 8 | Environments | ~45 min | Dev, UAT, and Production — branches, promotion, and config |
| 9 | Worktrees, Stash & Rebase | ~40 min | Advanced git workflows for multitasking |
| 10 | Claude Code + Git | ~45 min | AI-powered development — parallel agents and worktrees |
| 11 | Advanced Topics *(optional)* | ~30 min | Bisect, tags, GitHub Actions, .gitignore strategies |

## How It Works

This course is interactive and conversational. Each lesson is a Claude Code slash command that guides you through concepts, has you run real git commands in a playground repository, and checks your understanding before moving on.

You choose how to run exercise commands:
- **Paste them into Claude** for Claude to execute
- **Run them yourself** in a separate terminal

## Commands

| Command | Description |
|---------|-------------|
| `/start-course` | Begin the course from the beginning |
| `/resume-course` | Continue where you left off |
| `/course-status` | Check your progress |
| `/lesson-N` | Jump to a specific lesson (e.g., `/lesson-3`) |
| `/lesson-N <step>` | Jump to a specific step within a lesson (e.g., `/lesson-3 5`) |

## Getting Started

1. Clone this repository
2. Open Claude Code in the cloned directory
3. Run `/start-course`

Module 11 is optional and covers advanced topics you can explore after completing the main course.
