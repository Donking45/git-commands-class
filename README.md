# git-commands-class

## Explain Version Control
Version control keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing
disruption to all team members.

## Explain the Difference Between Git and GitHub
- **Git:** Git is a distributed version control system for tracking changes in source code during software development.
It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals 
include speed, data integrity and support for distributed, non-linear workflows.

- **GitHub:** GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management(SCM) functionality of Git as well as adding its own features.

## List 3 Other GitHub Alternatives
- **GitLab:** GitLab is a cloud-based Git and DevOps platform that helps developers monitor, test and deploy their code.

- **Bitbucket:** Bitbucket is a Git code management solution built for professional teams. It offer free plans for small
teams and has a stronger focus on Mercurial repositories.

- **SourceForge:** SourceForge is a web service that offers software consumers a centralized online location to control and manage open-source software projects and research business software.

## Explain the Difference Between Git Fetch and Git Pull
- **Git Fetch:** `git fetch` command is used to fetch all changes from the remote repository to the local repository. It does not make any changes to the current working directory. It stores all the changes in a separate branch called the remote-tracking branch.

- **Git Pull:** `git pull` command is used to fetch all changes from the remote repository to the current working directory. It automatically try to merge or rebase them into our current working directory. It is the combination of git fetch and git merge or git rebase. It can generate merge conflicts if there are conflict changes between our local and remote branches.


## Explain in Simple Terms Git Rebase and the Command for It
Git rebase is a process of integrating a series of commits on top of another base tip. It takes all commits of a branch and appends them to the commits of a new branch. The command is:  

```bash
git rebase <base>

```
## Explain in Simple Terms Git Cherry-Pick and the command for It
Git cherry-pick is a command used to commit from one branch and applying it to another. It allows you to select and include changes from one branch without merging the entire branch. The command is:

```bash
git cherry-pick <commit-hash>

