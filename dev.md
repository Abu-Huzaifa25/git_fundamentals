# Git Basics

## What is Git?
Git is a distributed version control system used to track changes in source code during software development. It allows multiple developers to collaborate efficiently.

## Common Git Commands

1. **Initialize a Repository**
    ```
    git init
    ```
    Creates a new Git repository in the current directory.

2. **Clone a Repository**
    ```
    git clone <repository_url>
    ```
    Copies an existing repository to your local machine.

3. **Check Repository Status**
    ```
    git status
    ```
    Displays the status of the working directory and staging area.

4. **Add Changes to Staging Area**
    ```
    git add <file_name>
    ```
    Stages changes for the next commit. Use `git add .` to stage all changes.

5. **Commit Changes**
    ```
    git commit -m "Commit message"
    ```
    Saves changes to the repository with a descriptive message.

6. **View Commit History**
    ```
    git log
    ```
    Shows the commit history of the repository.

7. **Push Changes to Remote Repository**
    ```
    git push origin <branch_name>
    ```
    Uploads local changes to the remote repository.

8. **Pull Changes from Remote Repository**
    ```
    git pull origin <branch_name>
    ```
    Fetches and merges changes from the remote repository.

9. **Create a New Branch**
    ```
    git branch <branch_name>
    ```
    Creates a new branch.

10. **Switch to a Branch**
     ```
     git checkout <branch_name>
     ```
     Switches to the specified branch.

11. **Merge Branches**
     ```
     git merge <branch_name>
     ```
     Merges the specified branch into the current branch.

## Tips
- Always write clear and concise commit messages.
- Use `.gitignore` to exclude files or directories from being tracked.
- Regularly pull changes to stay updated with the remote repository.
