# FIX SSL CERTIFICATE PROBLEM, SELF SIGNED CERTIFICATE

## **THE GLOBAL WORKAROUND**

    This happens with cloning the repository. Once the repository is cloned, this should not be an issue.

#### git config --global http.sslVerify false

    WARNING: This turns off ALL ssl certification for your git repos.

## **THE ONE TIME WORKAROUND**

#### git -c http.sslVerify=false clone "\<Repository Link\>"

    This only disables the ssl verification for this one command and allows you to clone the repo without the ssl verification.