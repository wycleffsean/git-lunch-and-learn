# Git Lunch & Learn

1. Git Terms and Objects

  refs
    - tags and branches
    - located in .git/refs

  tags & branches
    - are just pointers to a commit/sha
    - BRANCH advances with new commits
    - TAG always points to the same commit

  HEAD
    - special ref that points to current branch or commit

  the index
    - list of objects git is watching
    - new files are UNTRACKED, i.e. not in the index
    - altered files are TRACKED
    - `git add` causes files to be STAGED for commit

  reflog
    - record when the tips of branches and other
      references were updated in the local repository


2. Syntax
3. Common Options
4. Managing Changes
5. Committing Changes
6. Publishing Changes
7. Viewing Changes
8. Patching and Merging
9. Debugging
