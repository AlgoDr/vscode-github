# Hello From Github 
HEAD
commit->@algodr

## This is Second Commit
Author Commit @algodr
commit->@algodr !

## Local Development 
1. open index.html in the browser

### Tutorial on merging and pull request
when you create a feature(new branch to work in parallel apart from the main branch)
once the featured branch get ahead in the modifaction/changes in the code very well with no bug
the featured branch code is only updated in that branch not in the root/main  branch of the code 
once you checkout to main you see no changes in order to bring those changes to the main branch or any other branch 
you can checkout to that branch and merge it (But First You wanna create a pull request in feature branch)
& if you want to see the changes as in comparision with your code 

you have to create a pull request in feature branch(RECOMMENDED METHOD)
going  to github interface and go to compare and create pull request
you can see now the changes just like git diff command + are the added one - is the delted one and  blank wore the no change
now you have a pull request you can merge it to any branch in my case main
main is on the base and the feature branch which is merging to main will be pointing to the base : main branch
just like
base: main <- feature/2(feature branch) PULL REQUEST ON INTERFACE
and after that you can merge the request to pull the code to the main branch
by merging pull request (which is code of feature branch)

### TO DELETE BRANCH AnD ADD
To add
git checkout -b branch_name (-b for new branch to be added)
To delete 
git branch -d name-of-branch-to-be-deleted
(-d for the branch to be deleted)

### To Add and Commit same Tym 
 Whenever you made modification to your files your changes can be seen in git status command 
 so you first add thid as git add filenamea
 and than commit so what you can do is silmantaneously add and commit same time as a shortcut as

 git commit -am "what you did"
 -a for add
 and
 -m for commit message 
