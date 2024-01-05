# Demo

intructions for this demo.

now to update it.

## changes made

lololx


## github intro tutorial

to pull repo locally; use git clone
to check status of repo; use git status
to track after changes are made; use git add <filename> or git add .
to save changes to repo locally; use git commit -m "placeholder message" -m "description"
to save changes onto github; use git push <filename(s)>
nb: before that, we need to generate keys to allow transaction of files from our local machines onto our github accounts.
my keys are: id_rsa (private key) and id_rsa.pub (public key). the latter will be uploaded onto github and the earlier will serve as a key to upload files into the repo in my github account.

git push origin master
to add a local repo to github; use git remote add origin git@<repo-link.git>
check tracked repositories using; git remote -v
add a branch for file(s) upload; using git branch -M main
upload file(s) using git push -u origin main

git branching
to check the branches available for a repo; use git branch
to create a new branch; use git checkout -b <branch-name>
to switch between one branch to another; use git checkout <branch-name>
