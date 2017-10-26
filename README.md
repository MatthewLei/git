# useful git commands (DOUBLE CHECK BEFORE USING)

*  git clean -df (removes all untracked files from working tree) (-d includes directors, -f force / -n dry-run without changing)
*  git checkout -- . (clears all unstaged changes for tracked files)
*  git reset --hard <origin/master> (caution. resets head of local repo to head of remote repo)
*  git log -<number> (list the last <number> logs)
*  git log <another_branch>

# stashing

*  git stash list
*  git stash
*  git stash pop
*  git stash apply stash@{<revision>}
*  git stash drop stash@{<revision>}

# diff'ing

*  git diff <branch1_or_id1> <branch2_or_id2> -- filename

# fixing commit credentials
*  git config user.name <username>
*  git config user.email <email>
*  git -c "user.name=<uname>" -c "user.email=<email>" commit ...
