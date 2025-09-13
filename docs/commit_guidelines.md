# Commit Message Guidelines

We follow a consistent style for commit messages to make history readable and useful.

---

## Format

<type>: <short description>

[optional body]

[optional footer]


### 1. Types
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Code style changes (formatting, no logic)
- `refactor`: Code refactor without adding features or fixing bugs
- `test`: Adding or updating tests
- `chore`: Maintenance tasks (dependencies, config, etc.)

### 2. Description
- Use **imperative mood** → e.g., “add” not “added” or “adds”.
- Keep under **50 characters**.
- Be specific.

Example:  

feat: add task creation to CLI


Not good:  

fixed the bug in tasks


### 3. Body (optional)
- Provide details about *why* the change was made.
- Wrap lines at 72 characters.

Example:  

fix: correct calculation of task IDs
- Fixed bug where task IDs reset on restart
- Added unit test for regression


### 4. Footer (optional)
- Reference related Issues or PRs.
- `Fixes #12` → auto-closes Issue #12 when merged.

Example:  

feat: implement task deletion
- Added delete_task() function
- CLI command 'delete <id>'

Closes #5


---

## Workflow
1. Open an Issue before starting work.
2. Create a branch (`feature/...`, `bugfix/...`).
3. Commit changes with proper message format.
4. Push branch and open a Pull Request.
5. Link PR to Issue (`Fixes #id`).
6. Get review → Merge into main.
