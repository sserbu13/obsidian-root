#git #commit #push

Here's how to commit and push your changes using git commands:

1. First, check what files have been modified:

`git status`

1. Stage your changes (you can specify files or use `.` for all changes):

`git add .`

1. Commit your changes with a descriptive message:

`git commit -m "Update pytest.ini configuration and markers"`

1. Push your changes to the remote repository:

`git push origin main`

> Note: Replace `main` with your branch name if you're working on a different branch. You can check your current branch with `git branch`.

If you want to verify everything worked:

`git status`

This should show that your working directory is clean.