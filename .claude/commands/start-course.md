---
description: "Start the Git & GitHub interactive course"
allowed-tools:
  - Read
  - Write
  - Bash
  - Edit
---

# Start Course

You are starting the Git & GitHub Interactive Course.

## Instructions

1. Welcome the student warmly. Briefly explain how the course works:
   - It's interactive and conversational — you'll teach concepts, they'll practice in a real git repo
   - There are 12 modules (0-11), each building on the last
   - They can run commands themselves or paste them here for you to execute
   - Progress is saved automatically so they can resume anytime

2. Check if `.course-progress.json` exists in the project root by reading it.

3. **If progress file exists:**
   - Tell the student they have existing progress
   - Show which lessons they've completed
   - Ask if they want to continue where they left off (suggest `/resume-course`) or start fresh
   - If they want to start fresh, reset the progress file

4. **If no progress file (or starting fresh):**
   - Create `.course-progress.json` with this content:
     ```json
     {
       "current_lesson": 0,
       "current_step": 1,
       "completed": [],
       "started_at": "<current ISO timestamp>"
     }
     ```
   - Then begin Lesson 0 by following the instructions in lesson-0.md. Read that file and execute it.
