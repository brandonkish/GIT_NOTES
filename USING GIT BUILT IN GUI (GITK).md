# USING GIT'S BUILT IN GUI (GITK)

## **VIDEO REFERENCE**

#### https://youtu.be/WLL4GbdnuL8


## **OPEN GITK FOR FULL REPO HISTORY**

#### gitk --all &

    The --all opens the gui for all branches.

    Removing the --all will open up the GUI just for the currently selected branch.

## **OPEN GITK TO VIEW CHANGES TO A SECIFIC FILE ON CURRENT BRANCH**

#### gitk -- "\<filename\>" &

    Shows the history of a specific file in the in the current branch.

#### gitk --all --full-history -- "\<filename\>" &

    Shows the history of a specific file for EVERY branch.



## **WHAT THE TAGS MEAN (REFERENCES)**

    Local branches have tags that are colored green ONLY.

    Remote branches have "tan/green" tags that are mixed.


## **IDENTIFYING THE HEAD**

    Yellow dot means that the head is currently pointing to that commit.

## **FINDING ALL THE REFERENCES**

#### File > ListReferences

    This shows a list of all the tags and different branches in the repository.

    You can also search for a reference in the list at the bottom.

## **JUMP TO A COMMIT USING ITS HASH**

#### "SHA1 ID:" > Paste hash here > Hit Enter

    Doing this will allow you to jump to a specific commit in the repo.


## **SEARCH COMMIT**

#### Use the "find" box below the "SHA1 ID"
    You can specify what field to search through on the right.

    You can also make the search case insensitive on the right from the dropdown.

## **VIEWING THE OLD FILE VS NEW FILE**

#### Select "Old version" or "New version" 

    This will allow you to easily see the old version of the file vs the new version of the file, without having to look at the changes from one to the other.

## **VIEW ALL FILES IN COMMIT NOT JUST CHANGED FILES**

#### Select "Tree" instead of "Patch"

    The tree view shows every file in the commit, and shows thier file structure.

    Patch view shows just the files that have been changed from the previous commit.

## **DIFFING TWO COMMITS THAT ARE NOT CONSECUTIVE**

    Open the commit you wish to compare against by clicking it once in the tree view.

    Right click the commit you wish to compare against (Not selecting it) and select "Dif this -> selected" from the menu.

## **CREATE A FILE SHOWING THE DIFFERENCES BETWEEN COMMITS (PATCH)**

#### Right-click the commit and select "Make patch"

    This generates a "patch" file that shows the differences made in a commit. This is useful if you wish to send the file to someone else.