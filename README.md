# GitHub Demo

### Create Repo on GitHub

1. Create a repository on GitHub
2. Within the repo, create new file `test.txt`
3. Added the follwing lines below to the file on GitHub

- `This is dummy text`
- `I might add another line of dummy text.. but idk.`
- `This line was created on GitHub and is used to test pulling using the CLI.`

4. Once text is added, scroll to bottom and leave comment for changes
5. Click `add a commit`

### Clone from GitHub

1. Copy SSH url from GitHub Repo
2. Open terminal and type `git clone <paste SSH URL>`
3. Open file in VSCode
4. Add the following line

- `This line is being added from VSCode and is being pushed to GitHub.`

5. Save your changes then type `git status` in the terminal. This tells us if there are files with recent changes.
6. Next type `git add . && git commit -m "comment"`. "git add" tells git to add changes in the working directory to the staging directory, and "git commit" tells git to capture a snapshot of the projects currently staged changes.
7. Next type `git push`. This will push changes to the GitHub repo.
