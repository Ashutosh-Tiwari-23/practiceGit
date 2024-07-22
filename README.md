##Practicing git commands

## Commands

## Step 1: git init, to initialize the repository

## Step 2: git add , to track the changes/new addded files in the project. Files status changes from untracked to tracked. Note : to add all files together : git add .

## step 3: git status, to check the status of files added/removed

## staginng environment : an environment where we will keep all the added files in order to push to the repository later on

## step 4: git commit, after adding , w ewill create a stging environment locally and will push the changes.

## git commit -m "[information about the commit]", -m is for including the message. So basically commit is for moving the changes to staging environment

## after commit, the file has been moved to staging environment

## step 5: git branch is renamed to main branch/ master branch

## step 6: include the destination url of the repository

## git remote add origin https://github.com/ , the name origin is alias of the destination url. Note: Once the destination url is set, then this step is not required for the next changes until the destination remains same.

## final step : to push the code from main to the origin ( final destination)

## step 7: git push -u origin main

## step 4: git branch, to check the branch

### Pull the code

## git pull origin main : so this command will pull all the new changes from main to orogin

## Importance of gitignore : to avoid commit action on certain files that are not intended to be included/commit.

# So any specific files/folders that the deveoper does not want to send to the repository, those files/folders shpuld be included in gitignore

## Branching strategy : to create replica of the main branch : git branch "branch - Name"

# change of branch : git checkout branchName
