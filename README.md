# git-commands-class

EXPLAIN VERSION CONTROL
Version control is a system that records changes to a file or set of files
over time, allowing you to recall specific versions later. It facilitates
collaboration among multiple contributors, helps track changes, and provides
the ability to revert to previous states. This is crucial to work concurrently 
on projects while maintaining a coherent and traceable history.

EXPLAIN DIFFERENCE BETWEEN GIT AND GITHUB
-Git: Git is a distributed version control system that allows individuals
or teams to track changes in source code during software development. 
It operates locally on your machine and does not require a network connection.

-Github: Github, on the otherhand, is a web-based platform thhat provides
hosting for Git repositories. It enhances collaboration by offering features like
pull requests, issue tracking and project management. Github serves as a remote repository
for Git, making it easier for teams to collaborate and share code.

LIST 3 OTHER GITHUB ALTERNATIVES
-GitLab: Gitlab is a web-based Git repository manager that provides source code
management, continuous integration and more. It can be self-hosted or used as a 
cloud service.

-Bitbucket: Bitbucket is a Git and Mercurial code management platform. It offers
features like pull requests, code review and continuous integration. Bitbucket is
often used for both small and large scale projects.

-SourceForge: SourceForge is a web-based platform that provides version control,
bug tracking and collaboration tools. It supports Git, SVN(Subversion) and Mercurial.

EXPLAIN THE DIFFERENCE BETWEEN GIT FETCH AND GIT PULL
-Git Fetch: git fetch downloads changes from a remote repository but does not 
automatically merge them with your local branch. It updates your remote tracking 
branches, allowing you to review changes before merging.

-Git Pull: git pull fetches changes from a remote repository  and automatically
merges them into your current local branch. It combines the git fetch and git merge 
commands, providing a more streamlined approach.

EXPLAIN IN SIMPLE TERMS GIT REBASE AND THE COMMAND FOR IT
Git rebase is a command used to integrate changes from one branch into another
by moving or combining a sequence of commits. It is often used to maintain a clean and 
linear project history. The commmand is: 
  
    git rebase <base_branch>

EXPLAIN IN SIMPLE TERMS GIT CHERRY-PICK AND THE COMMAND FOR IT
Git cherry-pick is a command used to apply a specific commit from one branch
to another. It allows you to select and include changes from one branch without 
merging the entire branch. The command is:

    git cherry-pick <commit_hash>