# Steps to create a project locally and push it to GitHub

## Locally

### Step 1
Create a folder for your project

### Step 2
Create files in your folder.
For demonstration purpose: create README.md

### Step 3 
If we try `git status`, we get `fatal: not a git repository (or any of the parent directories): .git`.

We need to initialize a empty Git repository by: `git init`

After that, you can have `ls -la` to see the newly generated stuff (hidden) in the project folder.

### Step 4

Run the following instructions:

- `git status`
- `git add README.md`
- `git commit -m "Created README.md"`

## On GitHub
### Step 1
- Create an empty repo in GitHub with the same name.
- Then choose HTTPS. For this demo: https://github.com/tomhoi/Demo_Local_To_GitHub.git

## Back to local machine

### Step 1

Run the following instructions:

- `git remote add origin https://github.com/tomhoi/Demo_Local_To_GitHub.git`
- `git remote -v`

### Step 2:
Finally:

- `git push -u origin master`