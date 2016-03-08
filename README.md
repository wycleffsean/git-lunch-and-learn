# Git Lunch & Learn

1. Git Terms and Objects
2. Syntax
3. Common Options
4. Managing Changes
5. Committing Changes
6. Publishing Changes
7. Viewing Changes
  - `git log`
    - prettier view
    - `git log --all`
    - common options
      - `git log -- some/file.rb`
      - `git log start_ref..end_ref`
      - `git log -p`
      - compose them all
        `git log -p start_ref..end_ref -- some/file.rb`

  - `git blame -- some/file.rb`

  - `git show some_ref`

  - `git diff`
    - common options
      - `git diff -- some/file.rb`
      - `git diff start_ref..end_ref`
      - compose them
        `git diff start_ref..end_ref -- some/file.rb`

8. Patching and Merging
9. Debugging
