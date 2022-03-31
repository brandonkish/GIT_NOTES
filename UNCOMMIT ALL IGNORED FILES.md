## Uncommit all ignored files

git ls-files -i -c --exclude-from=.gitignore | %{git rm --cached $_}

NOTE: Use powershell to run this command