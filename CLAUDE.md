# Project Preferences

## Git Workflow — Cross-Device Continuity

- When finishing work or ending a session, **push directly to `main`** if there are no conflicts and the build passes. This makes work immediately available on any device with a simple `git pull`.
- If a feature branch is necessary (e.g., assigned by a task system, or work is experimental), **also leave a breadcrumb on `main`**: either update the README with a note about active branches, or create a small commit on main noting which branch has in-progress work and what the next steps are.
- Always make it easy to find in-progress work from any device. Assume the user may switch between phone and computer mid-task.
