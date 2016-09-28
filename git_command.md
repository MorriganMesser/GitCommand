# Git command and process

## No1.How to init a repository in local

1. Create a folder that you wish to be a repository

2. enter the command in the path

3. git init

4. git add <filename>

5. git commit -m "<Notes>"

6. git remote add origin git@github.com:<yourGitName>/<repositoryName>.git

7. git push -u origin master

8. Done!

## No2.How to clone a repository from origin

1. Open the url "github.com" and sign init

2. Check the page named "Repositories" and Click the key named "New"

3. Done create.

4. check in the folder that you want to clone the repository

5. enter the command in the path

6. git clone git@github.com:<yourGitName>/<repositoryName>.git

8. git add <filename>

9. git commit -m "<Notes>"

10. git push [origin <branchName>]

11. Done!

## No3.Pull and Fetch

### 1. git pull origin <branchName>

get the New version and merge the local

### 2. git fetch origin <branchName>:tmp

get the New version and not merge the local 

git diff tmp
git merge tmp

## No4. How to use Branches

### 1. git branch <branchName>

Create a new branch

### 2. git branch

Find out which branch are you in

### 3. git checkout <branchName>

Check to a branch

### 4. git checkout -b <branchName>

Create a new branch and check to it