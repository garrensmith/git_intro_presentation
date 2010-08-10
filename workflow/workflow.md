!SLIDE center
#Workflow
![junk](junk.jpg)

!SLIDE smaller bullets incremental transition=fade
#Best Practices Workflow part 1
* update master branch to latest 
(git rebase)
* create new branch for new feature 
(git checkout -b new_feature)
* code..code..code..code..code..code..
* commit to local branch anytime you want to until feature is complete 
(git add . => git commit -m "a commit message")

!SLIDE smaller bullets incremental transition=fade
#Best Practices Workflow part 2

* swich to master and get latest changes 
(git checkout master)
* switch back to feature branch and merge changes from master and resolve and conflicts. 
(git checkout new_feature => git merge master)
* switch back to master and merge trunk 
(git checkout master => git merge new_feature)
* push changes to trunk 
(git push origin master)

!SLIDE 

# DEMO
