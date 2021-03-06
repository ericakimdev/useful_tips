### How can I merge two branches?

```git checkout branch_a ```    &nbsp;&nbsp;&nbsp; You will switch to branch a.<br /><br />
```git merge branch_b```   &nbsp;&nbsp;&nbsp; This will merge all changes from branch b into branch a.<br /><br />
```git commit -a```   &nbsp;&nbsp;&nbsp; This will commit your changes.<br /><br />

### How can I copy remote branch to local?
```git fetch origin remote_branch_name:local_branch_name```  &nbsp;&nbsp;&nbsp;Create a local branch which is a copy of a remote branch.<br /><br />
```git switch remote_branch_name```  &nbsp;&nbsp;&nbsp;Create a local branch with the same name as the specified remote branch.<br /><br />


### git is not case sensitive, so even to rename the folder I had to do:
```git mv sendEmail tmp```<br /><br />
```git mv tmp SendEmail```<br /><br />

### How to delete multiple branches in Git
```git branch | grep "<pattern>"```
```git branch | grep "<pattern>" | xargs git branch -D```<br />

e.g.<br />
```git branch | grep "feature-*" | xargs git branch -D```<br /><br />
