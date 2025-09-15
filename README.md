# SS---Study-Point-Opgave-2

We use **GitHub Flow** as our branching strategy.

- Always branch off `main`.
- Use feature branches (`feature/xyz`) and bugfix branches (`bugfix/abc`).
- Open a Pull Request (PR) to merge into `main`.
- Require at least 1 approval before merging.

### Why GitHub Flow?
We chose GitHub Flow because:
- It is simple and lightweight, making it easy for the whole team to follow.
- It encourages small, frequent Pull Requests, which improves collaboration and code quality.
- It integrates well with GitHub Projects, Issues, and Actions (automation).
- It fits our project, where continuous integration and frequent deployments are more important than long-lived release branches.

## Development Environment (Dev Container)

This project provides a Dev Container setup so all contributors use the same environment.

### Prerequisites
- Install [Docker](https://www.docker.com/get-started)
- Install [Visual Studio Code](https://code.visualstudio.com/)
- Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### How to Open
1. Clone the repository:
   ```bash
   git clone https://github.com/Oliver-Goth/SS---Study-Point-Opgave-2.git
   cd SS---Study-Point-Opgave-2
2. Open the project in VS Code.

3. When prompted, “Reopen in Container” → VS Code builds and opens the dev container.

4. Run the project or tests:
   ```bash
   python src/main.py
   pytest

5. Commit & Push
   ```bash
   git add .devcontainer/devcontainer.json requirements.txt README.md
   git commit -m "chore: add devcontainer setup"
   git push origin feature/devcontainer


## Using This Project as a Starting Point

This repository is designed to be easily adapted for other projects, especially those involving scheduling, resource management, or booking systems. Here’s how you can get started:

### 1. Clone and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo

2. Install dependencies:
   ```bash
   npm install

3. Start the development server:
   ```bash
   npm start
The app will run at http://localhost:3000.

### 2.Customize the Backend
- The project currently uses a local backend at http://localhost:5240.
- To use your own backend, update the API endpoints in the src/api folder and adapt the data structures as needed.
- Ensure your backend returns data in a compatible format (e.g., users, resources, reservations).

### 3. Modify or Extend the UI
- The project uses React with TypeScript and Fluent UI for styling.
- Components in src/components can be modified, replaced, or extended for your own needs.
- For example, you can add new resource types, calendar views, or custom booking workflows.

### 4. Extend Functionality
- Follow the existing component and context structure for adding new features.
- You can add new routes by updating App.tsx.
- Use the src/Interface.tsx file to define and expand your own data types.

### 5. Use as a Boilerplate
- This project can serve as a boilerplate for other scheduling or management apps.
- Reuse the authentication system, booking popup structure, and calendar layout to save development time.

### 6. Tips
- Keep the component structure modular to make future adaptations easier.
- Document any changes you make to help others use your version as a starting point as well.
   ```pgsql
   If you want, I can also **write a shorter, more concise version** that fits neatly into an existing README without being too long. Do you want me to do that?
