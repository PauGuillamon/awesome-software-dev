GIT
================

Command line
----------------

* log
```
git log --pretty=format:"%h %ad%x09%an%x09%s" --graph --all
git log --graph --abbrev-commit --decorate --date=relative --all
```

* blame
From line 497, to line 497+50:
`git blame -L497,+50 [filename]`
http://stackoverflow.com/questions/8435343/retrieve-the-commit-log-for-a-specific-line-in-a-file

* Checkout remoting branch
`git checkout -b [branch_name] origin/[branch_name]`
`git checkout [branch_name]` if branch_name doesn't exist locally

* Push local branch
`git push -u origin [branch_name]`
http://stackoverflow.com/questions/2765421/how-to-push-a-new-local-branch-to-a-remote-git-repository-and-track-it-too

* Delete local branch
`git branch -D [branch_name]`

* Stage changes partially
`git add --patch [filename]`
http://stackoverflow.com/questions/1085162/commit-only-part-of-a-file-in-git

A successful git branching model
----------------

https://nvie.com/posts/a-successful-git-branching-model/

Submodules
----------------
https://git-scm.com/book/en/v2/Git-Tools-Submodules


Subtrees
----------------
http://apenwarr.ca/log/?m=200904#30
