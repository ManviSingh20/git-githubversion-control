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

1. git init main - Initiate a git
2. git status - Check which files are in the staging area.
3. git add <fileName> - Adding file to the staging area.
4. open -a <"App name"> <fileName> - Open file with a specific application.
5. git commit -m <"Message"> - Used to commit the files. Here, -m is the message tag.
6. git log - See what commits are made and when.
7. git add . - Add all the files in working directory to staging area.
8. git diff <filename> - Check the difference between the older file and the modified file.
9. git checkout <filename> - rollback or revert back to the last position in our local repository.

*Note:-
- Working Directory - It is a forlder or directory, where we initialize our git repository.
- Staging Area - It is an intermediate space where we can prepare and organize our changes before committing them to the repository. It acts as a buffer between our  working directory (where files are modified) and the commit history (the permanent record of changes).
- Git Repository - It is a storage space where your project's files and the entire history of changes are tracked using Git.













