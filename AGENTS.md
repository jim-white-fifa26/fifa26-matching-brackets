# AI Agents in this project

This project was built and maintained with the help of AI agents.

## Workflow Automation

This project includes an AI agent workflow for streamlined Git operations and pull request creation. The workflow automates the following tasks:

**Allowed Tools:**
- `Bash(git checkout --branch:*)` - Create and switch to new branches
- `Bash(git add:*)` - Stage changes
- `Bash(git status:*)` - Check repository status
- `Bash(git push:*)` - Push commits to remote
- `Bash(git commit:*)` - Create commits with messages
- `Bash(gh pr create:*)` - Create pull requests

**Workflow Process:**
1. Creates a new branch if currently on main
2. Creates a single commit with an appropriate message
3. Pushes the branch to origin
4. Creates a pull request using GitHub CLI

This automation enables efficient collaboration and code review processes for both human developers and AI agents working on the project.
