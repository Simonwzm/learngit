Git is a distributed version control system.
Git is a free software distributed under the GPL.
Git has a murable index called stage.
Git tracks changes of files.
have just move directory~
unexpect error~
Creating a new branch is quick and simple.
Branch name: dev
we can use git log --graph --pretty=oneline --abbrev-commit to show branches visually
In which the * represents a unique version.
new modify in branch de
we can use git merge --no-ff -m "xxx" <branch_name> 
to merge a branch without using fast-forward mode, which can 
preserve the information of this branch if we delete it some day
(because in this way we handle a commit to record its version information)
git config --global http.proxy http://127.0.0.1:7890 git config --global https.proxy http://127.0.0.1:7890
this is used to config proxy fixing git push bugs
try stash
feature vulcan:blablabla