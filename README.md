## Merge Conflicts

If master branch is pushed on from a user, all other users need to pull the new master before pushing any other changes.  Not doing so will cause a merge conflict for anybody after the first push.  If this happens, use git pull origin master to get the updated files that were missed.  Conflict markers from Git will be n the file where there were differences in the code.