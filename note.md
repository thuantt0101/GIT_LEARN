# Term

Repository (Repo)
Branch
Conflict
Local
Remote

For Example : GITHUB_VN is a Project Name = Repo 

# Commands

- git init
- git status
- git add
- git add . 
- git reset
- git commit
- git log
- git log --oneline
- git checkout [id of commit] 86bfe68
- git checkout {branch name}
- git branch
- git checkout -b {branch name}
- git merger {branch name}
- git branch -d {branch name} => [del a branch]

- git push {repo url} {branch name}=> [push local repo to remote repo]

- git remote add origin {repo url}  => [create remote repo alias] , for push just type [ git push origin master]
 
- git push origin {branch name }
- git push -u {alias} {branch name}
- git clone {repo url}
- git fetch origin : Fetches updates made to a remote repository
- git merge REMOTE-NAME/BRANCH-NAME # Merges updates made online with your local work
- git checkout -b {branch name} origin/{branch name}

- git pull {rego url} {branch name} => sync all change from remote repo to local repo
    --allow-unrelated-histories : option to be used in a rare event that merges histories of two projects that started their lives independently.
    git pull is a convenient shortcut for completing both git fetch and git merge in the same