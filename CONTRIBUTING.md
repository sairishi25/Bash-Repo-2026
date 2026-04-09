# Contributing Guide

We're excited you want to contribute to this repository! This guide will help you step-by-step to submit your very first Pull Request (PR).

## The Workflow

1. **Fork the Repository**
   Click the "Fork" button in the top right corner of this page to create your own copy of this repository on your GitHub account.

2. **Clone your Fork**
   Open your terminal and clone the repository you just forked:
   ```bash
   git clone https://github.com/<YOUR_USERNAME>/bash-training-repo.git
   cd bash-training-repo
   ```

3. **Create a Branch**
   Create a new branch for your task. Give it a descriptive name:
   ```bash
   git checkout -b fix-sys-info-script
   ```

4. **Make Your Changes**
   - Open the script file you want to work on inside the `scripts/` folder.
   - Look for the `# TODO:` comment and add the required bash code.
   - Test your changes locally to make sure it works!

5. **Commit Your Changes**
   Stage your changes and commit them with a meaningful message:
   ```bash
   git add scripts/<script-name>
   git commit -m "Add current user and hostname to sys-info"
   ```

6. **Push to Your Fork**
   Push the changes on your new branch to your forked repository:
   ```bash
   git push origin fix-sys-info-script
   ```

7. **Create a Pull Request (PR)**
   - Go to your forked repository on GitHub.
   - You should see a prompt to "Compare & pull request" for your recently pushed branch.
   - Click it, fill out the PR Template, and submit!

A maintainer will review your PR and merge it. Congratulations!
