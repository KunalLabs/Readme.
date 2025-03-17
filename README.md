##  Git

Git is a distributed version control system (VCS) designed to track changes in source code during software development. It allows multiple developers to collaborate on projects efficiently by managing revisions, facilitating team coordination, and enabling version control for files. Git tracks changes in a repository, stores these changes with metadata like authorship and timestamps, and supports branching and merging to facilitate parallel development efforts. It's widely used in software development to manage codebase versions and ensure project integrity across teams.

- git  --version


## Git Hub


GitHub is a cloud-based platform that uses Git for version control and collaboration. It allows developers to store, manage, and share their code repositories online. GitHub provides features like:

* Remote Repository Hosting: Store and access Git repositories online.
-Collaboration Tools: Supports team collaboration with pull requests, code reviews, and discussions.
-Branching and Merging: Developers can work on different features or fixes simultaneously.
-Issue Tracking: Manage bugs and feature requests efficiently.
-CI/CD Integration: Automate testing and deployment with GitHub Actions.
-Security & Access Control: Control who can view or edit your repositories.

### Remote to local Config

 ## SETUP

 Configuring user information used across all local repositories
 - git config --global user.name “[firstname lastname]”

 set a name that is identifiable for credit when review version history

 - git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker

 - git config  --list  
It show list configuration

- git clone <url>
- git status
- git add <filename>  or git add .
- git  commit -m "commit msg"
- git push origin main

### Local to Remote

- git init 
- git remote add origin  <link>
- git remote -v
- git branch
- git  checkout <branch name>
- git branch -d <branch name>
- git branch -M main
- git push -u origin main  (upstream)

### Merging code

- git diff <branch name >  
- git merge <branch name>


main

feature

### create pull request

git pull origin main

## Undoing changes

- git reset <filename>
- git reset 

* committed  changes

- git  reset HEAD~1

git log-history of commit
-  git reset --hard  [hashvalue]


## Resolve merge conflict

- git merge main
- git merge feture

git push
