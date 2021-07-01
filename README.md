#git basics

- `git init`: initialize git repository in current working directory
- `git status`: gives you the status
- `git add <FILE>`: add <FILE> to the staging area
- `git commit`: creates a commit, you provide message
- `git log`: shows your log for commits
   - `git log --oneline`; shows you the one line version og log
- `HEAD`: where your currently are (the version of the files on your computer)
- `git diff HEAD~<NUM> <FILE>`: ompares current file to file <NUM> ago
   -`git diff HEAD~<HASH> <FILE>`: ompares current file <HASH> version
- `git status` to help you find the commands to unstage or restore file
- `git checkout <HASH> <FILE>`: restore <FILE> to version in <HASH>
   - if you run `git checkout <HASH>` without the <FILE>
   - You an fix this running `git checkout main` 
