# Teamwork Guidelines
## Aim of this file
Given that many people in this group are using GitHub for project management and group collaboration for the first time, we believe that creating a guide document is necessary. Next, we will focus on explaining the group collaboration features of GitHub, including git branches, pull requests, and commit messages.
However, this file only introduce some basic actions for the early stage of project, it might need to be updated in the future.

## Branches
### Definition: Branches in Git are essentially separate lines of development. They allow you to work on different features, bug fixes, or experiments without affecting the main codebase.
### Usage: When working on a new feature or fixing a bug, you typically create a new branch from the main branch (often called master or main). This new branch serves as an isolated environment where you can make changes without affecting the main codebase. Once your changes are complete and tested, you can merge the branch back into the main branch.
### Example: If you're working on a feature called "User Authentication," you might create a new branch named user-authentication to develop that feature. Once the feature is complete, it can be merged back into the main branch.

## Pull Requests
### Definition: Pull requests (PRs) are proposals for changes to your repository. They let you tell others about changes you've pushed to a branch in your GitHub repository. Once a pull request is opened, you can discuss and review the potential changes with collaborators, and once approved, merge them into the main codebase.
### Usage: After you've made changes on a branch and are ready to incorporate them into the main codebase, you create a pull request. Other team members can review the changes, leave comments, and suggest modifications if needed. Once the changes are approved and any necessary discussions are resolved, you can merge the pull request into the main branch.
### Example: After completing work on the user-authentication branch, you might create a pull request to merge those changes into the main branch. Your teammates can review the changes, provide feedback, and ultimately approve the merge.

## Commit Messages
### Definition: Commit messages are brief descriptions of the changes made in a commit. They serve as a record of what changes were made, why they were made, and any relevant context for understanding the code changes.
### Usage: When you make changes to your code and are ready to save those changes, you create a commit. Along with the commit, you provide a descriptive message that explains the purpose of the changes. Clear and informative commit messages help you and your teammates understand the history of changes in the repository.
### Example: A commit message might be something like "Add user authentication feature" or "Fix bug in login functionality." It should succinctly describe the purpose of the commit and provide any necessary details to understand the changes made.