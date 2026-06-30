# how to push a local repository to GitHub

first, create a new repository on GitHub. Then, open your terminal and navigate to the local repository you want to push. Use the following commands:

1. git remote add origin <repository URL> - This command adds a remote repository to your local repository. Replace <repository URL> with the URL of your GitHub repository.

2. git branch -M main - This command renames the default branch to "main". You can skip this step if your default branch is already named "main".

3. git push -u origin main - This command pushes your local changes to the remote repository and sets the upstream branch.

4. If you have already committed changes, you can use git push to push those changes to the remote repository.
