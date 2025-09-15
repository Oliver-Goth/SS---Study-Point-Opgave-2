# Contributing to [SS - Study Point Opgave 2]

Thank you for considering contributing! This guide will help you get started quickly and follow the workflow we use in this repository. Following these guidelines ensures smooth collaboration and high-quality code.

---

## 1. Getting Started

### Clone the repository
  ```bash
  git clone https://github.com/Oliver-Goth/SS---Study-Point-Opgave-2.git
  cd your-repo
  ```
### Install dependencies
  ```bash
  npm install
  ```

### Using a Development Container (Optional)

If you are using VS Code Dev Containers:

1. Install the Remote - [Containers extension](https://code.visualstudio.com/docs/remote/containers)
2. Open the repository in VS Code.
3. Select Reopen in Container when prompted.
4. All dependencies and tools will be available inside the container.

## 2. Branching Rules
- Always branch off main.
- Branch naming conventions:
  - Features: feature/short-description (e.g., feature/login-form)
  - Bug fixes: bugfix/short-description (e.g., bugfix/calendar-bug)
  - Hotfixes: hotfix/short-description (for urgent fixes)

## 3. Commit Message Guidelines
- Use imperative mood (e.g., “Add login form” instead of “Added login form”).
- Reference related issues in commit messages when applicable:
  ```nginx
  Fixes #12
  ```
- Examples:
  - Add booking popup component
  - Fix calendar rendering bug
  - Update README with setup instructions

## 4. Creating a Pull Request
1. Ensure your branch is up-to-date with main.
2. Push your branch to the remote repository.
3. Open a Pull Request (PR) on GitHub.
4. PR description should include:
  - Summary of changes
  - Related issue(s) (e.g., Closes #45)
5. Request a review from at least one teammate.
6. Address any review comments before merging.
7. Once approved, merge the PR using Squash and Merge or Merge Commit depending on the project guidelines.

## 5. Code Style Rules
- Follow the existing TypeScript and React patterns.
- Use Prettier for formatting and ESLint for linting:
  ```bash
  npm run lint
  npm run format
  ```
- Consistency with component naming, file structure, and folder conventions is expected.
- For styling, follow Fluent UI guidelines.

## 6. Expected Workflow
1. Open an Issue describing a bug, feature request, or improvement.
2. Create a new branch from main following the branching rules.
3. Make changes locally.
4. Commit changes following commit message guidelines.
5. Push the branch and open a PR linking the Issue.
6. PR gets reviewed and approved.
7. Merge the PR.
8. Issue automatically closes if referenced with Closes #XX.

---

## Notes
- This file serves as the entry point for any new contributor.
- Following these guidelines helps reduce friction, ensures code quality, and makes collaboration smoother.
- If you have questions, open an Issue or reach out to the maintainers.
  ```yaml
  If you want, I can also **add a ready-made Pull Request template** that complements this CONTRIBUTING.md so new contributors have a form to fill when submitting PRs. This would make it even smoother for collaboration. Do you want me to do that?
  ```
