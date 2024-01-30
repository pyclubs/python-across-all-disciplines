---
description: Guide for Contributing to this Libraries Resource
---

# 🤝 How to contribute

## **Getting Started**

1. **Set Up Your Environment**
   * Ensure you have a GitHub account. If not, create one at [GitHub](https://github.com/join).
   * Install Git on your machine. Download it from [git-scm.com](https://git-scm.com/downloads).
2. **Fork the Repository**
   * Go to the GitHub repository where the resource is hosted.
   * Click the 'Fork' button at the top right corner to create a copy of the repository in your account.
3. **Clone the Repository**
   * Once forked, clone the repository to your local machine using the command: `git clone <URL of your forked repo>`.
   * Navigate to the cloned directory (`cd <repo-name>`).
4. **Set Upstream Remote**
   * To keep your fork synced with the original repository, set up an upstream remote: `git remote add upstream <URL of original repo>`.
   * Regularly fetch the changes from the upstream remote: `git fetch upstream`.

## **Making Contributions**

1. **Create a New Branch**
   * Create a new branch for your contribution: `git checkout -b <branch-name>`.
   * Keep branch names descriptive about the changes you're making.
2. **Make Your Changes**
   * Open the relevant files in your code editor and make your additions or modifications.
   * Ensure that your changes are well-documented and follow the existing format of the resource.
3. **Commit and Push Changes**
   * After making changes, stage them for commit: `git add .` (to add all changes) or `git add <file-name>` (for specific files).
   * Commit the changes with a clear message: `git commit -m "Add Python libraries for <Discipline>"`.
   * Push the changes to your fork: `git push origin <branch-name>`.
4. **Create a Pull Request (PR)**
   * Go to your forked repository on GitHub and click on 'New pull request'.
   * Select your branch and compare it with the original repository's main branch.
   * Fill in the PR template, explaining your changes and why they should be added.
   * Submit the PR for review.

## **Best Practices for Contribution**

* **Stay Updated**: Regularly pull changes from the upstream repository to avoid merge conflicts.
* **Documentation**: Clearly document your changes and follow the existing format.
* **Testing**: If applicable, test your changes to ensure they work as expected.
* **Communication**: Stay in touch with the maintainers. If you have questions or suggestions, open an issue on GitHub to discuss them.
* **Respect Guidelines**: Follow any contribution guidelines provided by the repository maintainers.
