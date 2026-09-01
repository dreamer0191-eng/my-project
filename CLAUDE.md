# Project Instructions

## task-observer skill activation

Before first tool call of any session — before writing or
proposing a plan, not merely before executing one — invoke the
task-observer skill AND execute its Session Start Protocol (storage
check, frontmatter scan, review trigger). Loading the skill and running
the protocol are separate steps; a session that loads the file and stops
is not activated, nothing has run.
Any turn that will involve a tool call counts; do
not classify a session as "too simple" from the opening message.

On completing a task, check what observation records were written this
session and report a one-line summary (ids and titles, or "none logged,
why").

When loading any skill, check the observation log for OPEN observations
tagged to that skill. Apply insights to current work, even if the
skill file hasn't been updated yet.

The observation log for this project lives at:
C:/project/skill-observations/observation-log/
Use this path. Never resolve the workspace from the current working
directory — a cwd inside an ephemeral checkout (a git worktree, temporary
clone) is torn down and takes the log with it. Never place the workspace
inside a skills-discovery directory or any path linked into one.
