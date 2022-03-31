## Remove committed file
   
git filter-branch --force --index-filter \

 'git rm --cached --ignore-unmatch ' **Path/to/file.ext** ' 

 --prune-empty --tag-name-filter cat -- --all