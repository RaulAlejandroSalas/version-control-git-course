# version-control-git-course

## Pull Requests I
The Pull Requests ist a feature of Git hosting site.The ultimate goal is to merge a branch into the project. Enable team communication related to the work of the branch.
* Notifications sent to team members
* Feedback or comments
* Approval of content(code review)

There are two basic repository configurations related to pull request. 
* The first is a single remote repository. A pull request is a single repository configuration.
* The second configuration involves two remote repositories , in this case a pull request is a request to merge a branch from a forked repository into the upstream repository. 

The second approach is common if the submitter doesn't have write access to the upstream repository. 

### When open a pull request?
* when the branch is created (enable the team to begin discussion on the work of the branch immediately)
* when you want comments on the branch
* when the branch is ready for review/merging

## Pull Request Single Repository
1- Create a feature branch
2- Optionally work on the feature branch
3- Push the branch to the remote repository

## Merge strategy for Pull Request
* **Merge commit**: the merge creates a separate commit object( `git merge --no-ff`)
* **Squash**: the entire branch is condensed to one linear commit(` git merge --squash`)