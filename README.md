Git Assignment 1
Overview
This repository contains practical exercises demonstrating Git fundamentals, local and remote repository workflows, branching, pull requests, resets, conflict resolution, and collaboration workflows.
Topics Covered
1. Local repository setup — initialize a repository, create files, commit to main, and practice staging/unstaging with git restore --staged and git reset.
2. Remote repository operations — connect a GitHub remote, push and pull changes, and inspect repository state with git status.
3. Branching and pull requests — create and fetch branches, commit branch-specific files, open a PR, and merge it into main.
4. Local Git operations — fetch/merge, soft and hard resets, interactive staging with git add -p, git diff, and git ls-files.
5. Branch merging and cleanup — merge b3 into b2, b2 into b1, and b1 into main; resolve a merge conflict; delete completed branches.
6. Fork workflow — fork the repository, clone the fork, push a change, and open a PR back to the original repository.
7. Advanced unstaging and stash challenge — stage and unstage selected changes, stash and reapply work, resolve any resulting conflict, and commit the resolution.
8. Additional operations — demonstrate rm and revert.
Repository
- Original repository URL: https://github.com/PrasadGit7/Git-Assn-1.git

Evidence / Terminal Screenshots
Store terminal screenshots in a folder named screenshots/. Use descriptive filenames, for example:
- 01-init-and-first-commit.png
- 02-stage-unstage-status.png
- 03-remote-push-pull.png
- 04-branch-and-pr.png
- 05-soft-reset-and-interactive-stage.png
- 06-hard-reset-and-diff.png
- 07-b1-b2-b3-merge.png
- 08-merge-conflict-resolution.png
- 09-fork-and-pr.png
- 10-stash-and-conflict-resolution.png
- 11-rm-and-revert.png
- 12-final-status-and-log.png
Capture genuine terminal output from your own completed lab. Make sure screenshots show the command and its result clearly. Do not add fabricated terminal output.
Useful Verification Commands
Run these from the repository directory before submission:
git status
git branch -a
git remote -v
git log --oneline --graph --decorate --all
git ls-files
Confirm the working tree is in the expected state, the remote URL is correct, and the required commits/branches are present. Push any final README or assignment changes to the remote repository.
Submission Checklist
- [ ] README updated with the real repository URL.
- [ ] PR links added and verified.
- [ ] Terminal screenshots captured for each major step and saved under screenshots/.
- [ ] Screenshots added to the repository and pushed.
- [ ] Final changes pushed to the remote repository.
- [ ] Repository URL copied for submission.
