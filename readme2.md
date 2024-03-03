# Git Workflow Guide

Follow these steps to effectively collaborate on a Git repository:

1. **Clone the Repository**: Begin by cloning the repository you intend to work with.
    ```bash
    git clone <URL-to-repo>
    ```

2. **Navigate to the Repository**: Move into the cloned repository directory.
    ```bash
    cd <repo-directory>
    ```

3. **Create a New Branch**: For each new set of changes, create a dedicated branch.
    ```bash
    git checkout -b <branch-name>
    ```

4. **Make Changes**: Implement the desired changes in the codebase.

5. **Stage Changes**: Selectively stage the changes you want to include in the commit.
    ```bash
    git add <file-name>
    ```
    or to add all changes:
    ```bash
    git add .
    ```

6. **Commit Changes**: Provide a descriptive commit message summarizing the changes made.
    ```bash
    git commit -m "Description of the changes"
    ```

7. **Push Changes**: Push the committed changes to the corresponding branch on GitHub.
    ```bash
    git push origin <branch-name>
    ```

By following this structured workflow, you can effectively manage your contributions to the project and maintain a clear history of changes.
