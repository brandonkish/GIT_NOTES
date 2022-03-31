## Revert one file
WARNING: Commit all changes first as this will overwrite local files!

git checkout **CommitNum** -- **Path/To/File**
git add **Path/To/File**
git commit -m **Message**


## Revert to previous commit
git reset --hard **Commit ID**
git push -f **Remote** **Branch**
