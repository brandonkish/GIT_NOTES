# SAVE UNSAVED CHANGES FOR LATER (STASHES)

## **SAVE FILES TO STASH**

#### git branch "<New Branch Name>"

    Creates a new stash which can store any changes you don't want to commit.

    -u: Causes git to store files that have been recently added to the repo, but are not currently tracked (Not been commited yet.)

    -m: allows you to apply a specific name to the stash

## **REVIEW CHANGES IN THE STASH**

#### **git stash list**

    Shows a list of all your stashes.

#### **git stash show -p \<index from list\>**

    Shows the current changes between the stash and our current branch's repo.
    The -p specifies to show the whole page file. Instead of only the specific areas with changes.

## **RETURN FILES BACK TO THE BRANCH**

#### **git stash apply \<index from list\>**

    Apply the changes from the stash to the current branch.

## **CREATE NEW BRANCH FROM STASH**

#### **git stash branch \<Branch Name> \<Index From List\>**

    Creates a new branch from the stash in the list.

## **REMOVE LAST STASH FROM LIST**

#### **git stash drop**

    WARNING: Will instantly remove stash from list.
    
    Removes the top most stash and applies it to the repo. This will delete the stash from the list.

    Recommended to use "git stash apply" instead then use "git stash drop" to remove it manually.

#### **git stash pop**

    WARNING: Will instantly remove stash from list.
    
    Removes the top most stash and applies it to the repo. This will delete the stash from the list.

    Recommended to use "git stash apply" instead then use "git stash drop" to remove it manually.

## **CLEAR ENTIRE STASH LIST**

#### **Git stash clear**
    
    Completely clear the list of stashes