# Git Tutorial
This is a tutorial for using git on your local system. Firstly, you need to install git and vscode on your local system. Providing the links for installation below:
- VSCode - [Installation Link](https://code.visualstudio.com/download)
- Git - [Installation Link](https://git-scm.com/downloads)

## Cloning Repository
The following are the steps to clone repository in your local system:
1. Switch to the folder you want to clone the repository.
2. Right click and click on Git Bash here.
3. In the Git Terminal enter the below code to clone repository.
```
git clone <ENTER LINK OF GIT REPO>
```
4. Change directory to the cloned repo.
```
cd "<REPO NAME>/"
```
## Creating your own branch
To create your own branch use the command below:
```
git checkout -b <ENTER NAME FOR YOUR BRANCH>
```

## Launch VSCode 
To launch VSCode (ensure you are in the directory where you want to launch vscode) use the below code:
```
code .
```

## Adding files
- To add new files use the below code:
```
git add "<FILENAME>"
```
- To add modified files use the below code:
```
git add -u
```

## Commit files
Once the files are added to commit the files use the below code
```
git commit -m "<ADD COMMENTS>"
```

## Pushing files to your branch
Use the below code to push the added and commited changes to the repository:
```
git push -u origin <BRANCH NAME>
```
