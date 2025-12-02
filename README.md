# Pull Shark Demo

Welcome to the Pull Shark Demo — a friendly, beginner-focused repository that demonstrates how GitHub pull requests, branches, and collaboration work in practice.

## Quick overview

This repository is a hands-on exercise to help you learn:
- How to fork a repository and work with branches
- How to make meaningful commits and open a pull request (PR)
- How to handle review feedback and merge changes

## Prerequisites

- A GitHub account
- Basic familiarity with git (clone, branch, commit, push)
- (Optional) Git installed locally if you want to work from your machine

## Quick start — make your first contribution

1. Fork this repository (click "Fork" at the top-right of the repo page).
2. Clone your fork:
   ```bash
   git clone https://github.com/<your-username>/pull-shark-demo.git
   cd pull-shark-demo
   ```
3. Create a new branch:
   ```bash
   git checkout -b improve-readme
   ```
4. Make changes (edit README, add a file, or fix a typo).
5. Stage and commit:
   ```bash
   git add .
   git commit -m "Improve README: clearer steps and examples"
   ```
6. Push your branch to your fork:
   ```bash
   git push origin improve-readme
   ```
7. Open a Pull Request:
   - Go to your fork on GitHub → click "Compare & pull request"
   - Make sure the base repo points to the original repository (not your fork)
   - Fill in the PR template and submit

## Good PR practices

- Use a clear, descriptive title
- Explain what changed and why in the PR body
- Keep changes small and focused per PR
- Reference related issues where appropriate, e.g. `Fixes #3`
- Use meaningful commit messages (imperative tense)

PR checklist (example)
- [ ] Title and description are clear
- [ ] Tests (if any) added or updated
- [ ] Linting / formatting checks pass
- [ ] Changes limited to the intended scope

## What you'll learn

Working with this demo will help you understand:
- Forking and branching workflows
- Opening and reviewing pull requests
- Collaborative development practices on GitHub

## Technologies

- Markdown for docs
- Git & GitHub for version control and collaboration

## License

This project is open source and available under the MIT License.

## Acknowledgements

Thanks to the open-source community for making learning and collaboration accessible to everyone. Happy contributing! 🦈
