# worldcup-database-solution

## Setting Up Your Own Remote Repository

If you want to push this project to your own GitHub repository, follow these steps:

1. Create a new repository on GitHub (you can name it whatever you like)

2. Add your repository as a remote:
```bash
git remote add myrepo https://github.com/TU_USUARIO/TU_REPOSITORIO.git
```
Replace `TU_USUARIO` with your GitHub username and `TU_REPOSITORIO` with your repository name.

3. Push your code to your repository:
```bash
git push myrepo main
```

Note: This repository uses `main` as the default branch. If your repository uses a different default branch name (like `master`), adjust the command accordingly.

### Alternative: Pushing to Master Branch

If you need to push to a `master` branch specifically:
```bash
git push myrepo HEAD:master
```

This will push your current branch to the `master` branch on your remote repository.