# Kanban Archive

**Purpose:** Long-term storage of completed tasks. Keeps main KANBAN.md lean and fast.

---

## Archive Structure

Each month gets its own file:
- `2026-01-completed.md`
- `2026-02-completed.md`
- `2026-03-completed.md`

**Format:** Same as main Kanban (markdown with metadata)

---

## Archival Policy

**Main KANBAN.md keeps:**
- Last 15 completed tasks
- All active work (IN PROGRESS, WAITING, BACKLOG, IDEAS)

**Automatically archived:**
- First day of each month (via Ops specialist)
- Tasks completed more than 30 days ago
- Moved from main Kanban to `/archive/YYYY-MM-completed.md`

---

## Searching Archives

```bash
# Find a specific task
grep -r "Task Name" /Users/daneel/clawd/projects/archive/

# Find all tasks from January 2026
cat /Users/daneel/clawd/projects/archive/2026-01-completed.md

# Count completed tasks in a month
grep "###" /Users/daneel/clawd/projects/archive/2026-01-completed.md | wc -l
```

---

*Maintained by Ops Specialist • Auto-archived monthly*
