---
description: "Resume the Git & GitHub course where you left off"
allowed-tools:
  - Read
  - Write
  - Bash
  - Edit
---

# Resume Course

## Instructions

1. Read `.course-progress.json` from the project root.

2. **If no progress file exists:**
   - Tell the student there's no saved progress
   - Suggest running `/start-course` to begin

3. **If progress exists:**
   - Show the student their progress:
     - Completed lessons (with names)
     - Current lesson number and name
     - Current step within that lesson
     - When they started the course
   - Say: "Let's pick up where you left off — Lesson {N}, Step {M}."
   - Read the corresponding lesson file (`.claude/commands/lesson-{N}.md`) and resume from step {M}.

## Lesson Names Reference
- 0: Course Setup
- 1: Why Version Control?
- 2: Repos & Commits
- 3: Branches
- 4: Merging & Conflicts
- 5: Remotes & GitHub
- 6: Pull Requests & Code Review
- 7: Collaboration Workflows
- 8: Environments: Dev / UAT / Prod
- 9: Worktrees, Stash & Rebase
- 10: Claude Code + Git
- 11: Advanced Topics (Optional)
