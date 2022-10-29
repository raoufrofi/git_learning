# Git

It is a version control system which is used by developers to work on the same project  
Any change made can be detected and it is saved and decelopers can jump back to the old version  
If more than one developer are working on the same project then the original branch will not be changed

1. Local and remote repos
2. Who made what changes and when
3. Revert back at any time
4. Coordinate work between multiple developers

## Basic Commands

### Local Repositry

1. **git init**

- Initialize a git repository

2. **git add**

- add a file to the staging area

3. **git status**

- check what's in the staging area

4. **git commit**

- get everything from stagin area and send it to the local repo

### Remote Repositroy

5. **git push**

- take local repo and push it to the remote repo such as github gitbucket
- it will ask details before pushing
  - which VCS(version control system) i.e, github,gitbucket
  - passwords and other stuff

6. **git pull**

- to pull latest changes from github or gitbucket

7. **git clone**

- clone the repo from github to local machine

# Other Commands

### touch filename

will create a file

### git config --global user.name ''

setting name it does not matter whether it matches with the github username or not

### git config --global user.email ''

this should be same as of github email addresses

### git add 'filename'

add a file to staging area

### git add \*.html or file extension

it add all files of the same extension

### git add .

add all files

### git rm --cached 'filename'

remove the file from staging area

### git status

check what's on the staging area

### git commit

will get you to some ui where you will type insert and then remove comment of initial commit command and then press esc to remove from the insert mode and then type :wq press enter your staging stuff will be commited

# OR

### git commit -m 'message of choice';

## CREATING BRANCH

### git branch branchname

### git checkout branchname

take you to that branch

# Pusing To Repo

## git push -u origin branchname
