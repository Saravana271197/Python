# Github demo Python scripts
# Assignment 2 IAC

This project is about creating a repository, pushing an existing folder into that git repository, creating new branch, making changes in the folder and committing those changes in the new branch Feature created before, the next step would be to merge the Feature branch with the main default branch by doing so all the changes done in Feature branch will be synced with main branch, by pushing all changes from main branch there will be successful push of all new changes committed in Feature branch into main branch.

Multiple commit sequences will be combined into a single, unified history using git merge. Git merge is most frequently employed to unite two branches. This document will emphasize this branch merging pattern in the examples that follow. In these cases, git merge will look for a common base commit between two commit pointers, typically the branch tips. Git will construct a new "merge commit" that incorporates the changes of each pending merge commit sequence once it discovers a common base commit.

The programmer primarily maintains a clean master branch in their git repository. They are then making a duplicate of the master branch where they can conveniently keep their most recent code updates, resolve any errors, commit the changes, and do a number of other actions. Simply branching in the git structure is what this technique entails. The git Branch command allows users to create, delete, list, and rename branches. One of the newest capabilities of git for maintaining code version control is branching. It displays the most recent version of your code without changing the master branch.

In this project we have created a python repository, included the exercise folder from week 1-9, need to create one repository in git named Python, this python repo will have only one default branch that is named main. Commit the folders and all files included in that folder, we use command git init for initialization of git in that particular folder where the project needs to be pushed. After git init we can add the contents inside the folder to git repo using git add and commit all the files to git repository using command git commit, and then finally push the folder contents to the git repository this will by default push the folder to main brnach. Below image shows the pushed repository Python.

![Python_folder_made_as_git_repo'](https://user-images.githubusercontent.com/74722748/210649760-4c4a2498-a31e-40c4-9be8-f2fe2d5b50ad.png)

Branch Feature needs to be created and to change the branch we use git checkout command, this changes the branch to whcihever branch is created and is given, the branch creation can be done using git brnach -b branchname (Feature). After branch creation use checkout command to change the branch from default main and then add and commit the changes made in the folder repo. Now to merge the changes made in Feature branch use command git merge -b Feature, this will merge the Feature branch chanmges with the main branch and main branch will be synced with Feature branch, then finally we can push it. Below image shows the creation of Feature branch.

![git_branches_feature_and_main_merged](https://user-images.githubusercontent.com/74722748/210652043-90636b97-8a5e-4c73-88f5-c9b46be1f6c0.png)



