# HOW TO NEST ANOTHER REPO INSIDE OF YOURS (SUBMODULES)

## **WHAT IS A SUBMODULE AND WHY USE IT?**

    A sub module is basically a nested repository. It allows you to keep the nested repository updated along with your own. If you just copy these files, then they will not reflect any changes / updates. When you add them as a nested submodule you can use the "submodule update" command to update them to the latest version inside your own repo. This is a useful alternative to using a package manager i.e. Gradle.

## **HOW TO ADD THE SUBMODULE TO YOUROWN**

#### git submodule add "\<Repository Link\>"

    To nest a repository from GitHub, navigate to the GitHub repository and copy its link. Use this link to add a reference (to nest) the repository in your own.

    You will still have to update it manually using the "update remote" command. See below.

## **MANUALLY UPDATE THE SUBMODULE (NESTED REPO)**

#### In the submodule directory in your repo > git submodule update --remote

    This command will update the submodule (Nested repository) in your project to the latest version it has on the remote.