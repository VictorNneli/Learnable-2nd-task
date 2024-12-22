## Explain Version Control
Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time. As development environments have accelerated, version control systems help software teams work faster and smarter.

## Explain the Difference Between Git and GitHub

**Git**:  
Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

**GitHub**:  
GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git, as well as adding its own features.

## List 3 Other GitHub Alternatives
- GitLab
- Bitbucket
- AWS Code Commit

## Explain the Difference Between `git fetch` and `git pull`

- **`git fetch`**:  
  The `git fetch` command is used to fetch all changes from the remote repository to the local repository. It doesn’t make any changes to the current working directory. It stores all the changes in a separate branch called the remote-tracking branch. The `git merge` or `git rebase` command is used to merge these changes into the current working directory.

- **`git pull`**:  
  The `git pull` command is used to fetch and integrate the changes present in the remote repository into the local repository.

## Explain in Simple Terms `git rebase` and the Command for It
To rebase the current branch onto another branch, run:  


