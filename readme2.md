# Git Workflow Guide

#First time setup
**Choose the Repository**: Get the link of the repo you want to push to: 
```bash
git remote add origin <url to repo>
```

Enhance your collaborative Git experience with these straightforward steps:

1. **Clone the Repository**: Begin by cloning the repository you wish to contribute to. This creates a local copy of the project on your machine, allowing you to work on it.
    ```bash
    git clone <URL-to-repo>
    ```
   
2. **Navigate to the Repository**: Move into the directory of the cloned repository to start working on it.
    ```bash
    cd <repo-directory>
    ```

3. **Create a New Branch**: Each set of changes should reside in its own branch, providing a clean and organized way to manage modifications without affecting the main codebase.
    ```bash
    git checkout -b <branch-name>
    ```

4. **Make Changes**: Implement the desired modifications, whether they involve adding new features, fixing bugs, or enhancing existing functionalities.

5. **Stage Changes**: Choose which changes to include in the next commit by staging them. This allows for granular control over the content of each commit.
    ```bash
    git add <file-name>
    ```
    To add all changes:
    ```bash
    git add .
    ```

6. **Commit Changes**: Commit the staged changes with a descriptive message, summarizing the purpose and scope of the modifications.
    ```bash
    git commit -m "Description of the changes"
    ```

7. **Push Changes**: Share your committed changes with others by pushing them to the corresponding branch on the remote repository, typically hosted on platforms like GitHub.
    ```bash
    git push origin <branch-name>
    ```

By following these steps, you can seamlessly contribute to Git repositories while maintaining a clear and organized workflow.
