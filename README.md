# Project Commands Guide

This README provides essential commands for working with Git & GitHub, Shopify CLI, and VS Code terminal to facilitate version control and theme development workflows.

---

## Table of Contents

- [Git & GitHub Commands](#git--github-commands)
- [Shopify CLI Commands](#shopify-cli-commands)
- [VS Code Terminal Commands](#vs-code-terminal-commands)
- [Contributing](#contributing)
- [License](#license)

---

## Git & GitHub Commands

- **Clone repository:**  
  `git clone <repo-url>`  
  Clone a remote GitHub repository to your local machine.

- **List branches:**  
  `git branch`  
  Show all branches available locally.

- **Create and switch branch:**  
  `git checkout -b <branch-name>`  
  Create a new branch and switch to it.

- **Switch branch:**  
  `git checkout <branch-name>`  
  Switch to an existing branch.

- **Check status:**  
  `git status`  
  Display modified and untracked files.

- **Stage changes:**  
  `git add .`  
  Stage all modified files for commit.

- **Commit changes:**  
  `git commit -m "commit message"`  
  Commit staged changes with a descriptive message.

- **Pull latest main branch:**  
  `git pull origin main`  
  Fetch and merge changes from the remote main branch.

- **Push to remote branch:**  
  `git push origin <branch-name>`  
  Upload local commits to the specified remote branch.

- **Create Pull Request:**  
  Use GitHub UI to open a pull request for review and merging.

---

## Shopify CLI Commands

- **Login to Shopify store:**  
  `shopify login --store <store-url>`  
  Authenticate your CLI with the specified Shopify store.

- **Initialize or clone theme:**  
  `shopify theme init [--clone <repo>]`  
  Create a new theme or clone an existing repository.

- **Serve theme locally:**  
  `shopify theme serve`  
  Preview theme changes on a local development server.

- **Pull theme from Shopify:**  
  `shopify theme pull`  
  Download theme updates from the live store.

- **Push theme to Shopify:**  
  `shopify theme push`  
  Upload local theme changes to the Shopify store.

- **List available themes:**  
  `shopify theme list`  
  Display all themes on the connected store.

- **Open theme in admin:**  
  `shopify theme open`  
  Open the selected theme in the Shopify admin dashboard.

---

## VS Code Terminal Commands

- **Open terminal:**  
  - Windows/Linux: `Ctrl + \`  
  - Mac: `Cmd + \`

- **Navigate directories:**  
  `cd <folder-name>`  
  Change the current directory.

- **List files:**  
  - Mac/Linux: `ls`  
  - Windows: `dir`

- Execute Git and Shopify CLI commands directly from the terminal.  
- Use VS Code UI to open, edit, and save files efficiently.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with detailed descriptions of your changes.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

*Last updated: October 6, 2025*

