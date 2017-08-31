# useful git commands (DOUBLE CHECK BEFORE USING)

*  git clean -df (removes all untracked files from working tree) (-d includes directors, -f force / -n dry-run without changing)
*  git checkout -- . (clears all unstaged changes for tracked files)

# stashing

*  git stash list
*  git stash
*  git stash pop
*  git stash apply stash@{<revision>}
*  git stash drop stash@{<revision>}
