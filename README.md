# Git, GitHub & Version Control

## Git

Git is a distributed version control system (VCS) that tracks changes in source code during software development. It allows multiple developers to work on a project simultaneously without overwriting each other’s changes. With Git, we can:
- Track the history of changes.
- Revert to previous versions of code if necessary.
- Create and manage branches for working on new features or fixes without affecting the main codebase.
- Merge changes from different branches back into the main project.

## GitHub

GitHub is a cloud-based platform that hosts Git repositories. It provides a user-friendly interface for collaborating with others on projects. GitHub allows developers to:
- Store code online and share it with others.
- Collaborate with teams through features like pull requests, code reviews, and discussions.
- Manage issues, bugs, and enhancements.
- Integrate with CI/CD tools (like Jenkins), making it easier to automate testing, building, and deploying applications.

*Note - While Git is the underlying tool that handles version control, GitHub adds social features like project management and team collaboration.

## Version Control

Version control is a system that records changes to files over time, enabling developers to:
- Track the history of code development.
- Collaborate on code without conflicts.
- Keep different versions (or branches) of a project, allowing experimental changes or new features to be developed without disrupting the main project.
- Roll back to previous versions of the code in case something goes wrong.

## Git Commands

1. git init - Initiate a git
2. git checkout -b main - Make main the default branch after initializing the repository.
3. touch <filename> - Create a file.
4. git status - Check which files are in the staging area.
5. git add <fileName> - Adding file to the staging area.
6. open -a <"App name"> <fileName> - Open file with a specific application.
7. git commit -m <"Message"> - Used to commit the files. Here, -m is the message tag.
8. git log - See what commits are made and when.
9. git add . - Add all the files in working directory to staging area.
10. git diff <filename> - Check the difference between the older file and the modified file.
11. git checkout <filename> - rollback or revert back to the last position in our local repository.
12. git remote add <name> <url-of-our-remote-repo> - Tells local repo that we have created a remote repo.
13. git push -u <remoteName> <BranchName> - Use to push things from our local repo to our remote repo.
14. git rm --cached -r . - Remove files from the staging area.
15. touch .gitignore - Create a .gitignore file.
16. git clone <repo-url> - Clone a remote repo to our local machine.
17. git clone -b <branch_name> <repository_url> - Clone a specific branch.
18. git branch <BranchName> - Creating a Branch.
19. git checkout -b <branch_name> - Create and switch to a new branch in one step.
20. git checkout <branch_name> - To switch between branches.
21. git merge <branch_name> - Merge it back into the main branch. (Firstly change branch to main - git checkout main).
22. git branch -d <branch_name> - Delete branch after merging. 

Note:-
- Working Directory - It is a forlder or directory, where we initialize our git repository.
- Staging Area - It is an intermediate space where we can prepare and organize our changes before committing them to the repository. It acts as a buffer between our  working directory (where files are modified) and the commit history (the permanent record of changes).
- Git Repository - It is a storage space where your project's files and the entire history of changes are tracked using Git.

## .gitignore

A .gitignore file is used in Git to specify which files or directories should be ignored by Git when committing changes. This is useful for excluding unnecessary files, such as temporary files, build artifacts, or sensitive information, from being added to a repository.

We can simply write the name of the files, which we do not want to commit, in .gitignore file. We have to follow the naming conventions.

## Cloning

Git cloning refers to creating a local copy of an existing remote Git repository onto your machine. It is essential for several reasons:
1. Collaboration: Allows team members to work on a shared project by creating a local copy of the repository.
2. Version Control: Brings the entire project history, branches, and tags, enabling tracking of changes and reverting to previous versions.
3. Local Development: Developers can work offline and push changes later.
4. Syncing: Keeps local copies up to date with the latest changes from the remote repository.
5. Experimentation: Enables safe testing of new features in isolated branches without affecting the main codebase.

## Branching & Merging

### Branching

Branching in Git allows you to create independent lines of development within a project. Each branch can represent a different feature, bug fix, or experiment, enabling parallel work without interfering with the main codebase.

Benefits of Branching:
- Isolation: Each branch can be developed independently, minimizing conflicts.
- Parallel Development: Multiple features or fixes can be worked on simultaneously.
- Experimentation: You can try out new ideas without affecting the main codebase.

### Merging

Merging in Git is the process of integrating changes from one branch into another. It allows you to combine the work done in different branches, typically bringing features or fixes into the main branch.

Types of Merging:
- Fast-Forward Merge: If the target branch has not diverged, Git simply moves the pointer forward to the latest commit of the source branch.
- Three-Way Merge: If there have been changes on both branches, Git creates a new merge commit that reconciles the two histories.

Benefits of Merging:
- Integration of Work: Combines multiple developers' contributions seamlessly.
- Maintains History: Keeps a record of all commits, including those from branches, preserving the project's history.





