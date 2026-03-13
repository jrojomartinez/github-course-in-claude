---
description: "Check your Git & GitHub course progress"
allowed-tools:
  - Read
  - Bash
---

# Course Status

## Instructions

1. Read `.course-progress.json` from the project root.

2. **If no progress file exists:**
   - Tell the student: "No course progress found. Run `/start-course` to begin."

3. **If progress exists:**
   - Display a formatted progress table like this:

   ```
   Git & GitHub Interactive Course — Progress
   ============================================
   Started: {started_at}
   Current: Lesson {N} — {name}, Step {M}

   Module  Status  Time     Name
   ------  ------  ----     ----
     0      [x]    ~20 min  Course Setup
     1      [x]    ~25 min  Why Version Control?
     2      [ ]    ~30 min  Repos & Commits  <-- current (step 3/6)
     3      [ ]    ~30 min  Branches
     4      [ ]    ~40 min  Merging & Conflicts
     5      [ ]    ~40 min  Remotes & GitHub
     6      [ ]    ~45 min  Pull Requests & Code Review
     7      [ ]    ~35 min  Collaboration Workflows
     8      [ ]    ~45 min  Environments: Dev / UAT / Prod
     9      [ ]    ~40 min  Worktrees, Stash & Rebase
    10      [ ]    ~45 min  Claude Code + Git
    11      [ ]    ~30 min  Advanced Topics (Optional)

   Estimated time remaining: ~X hours Y minutes
   ```

   - Use `[x]` for completed lessons, `[ ]` for incomplete
   - Mark the current lesson with `<-- current (step M/total)`
   - Use the total steps per lesson: 0:7, 1:7, 2:6, 3:7, 4:8, 5:9, 6:9, 7:8, 8:9, 9:9, 10:11, 11:6

4. **Calculate estimated time remaining:**
   - Use these estimated minutes per lesson: 0:20, 1:25, 2:30, 3:30, 4:40, 5:40, 6:45, 7:35, 8:45, 9:40, 10:45, 11:30
   - For the current lesson: estimate the remaining fraction based on (total_steps - current_step + 1) / total_steps * lesson_minutes
   - For all subsequent incomplete lessons (excluding lesson 11 unless it's the current or a completed one): add their full estimated minutes
   - Display the total as "Estimated time remaining: ~X hours Y minutes" (or just "~Y minutes" if under 60)
   - Lesson 11 is optional — if not yet started, show it separately: "Optional Module 11: ~30 min additional"
