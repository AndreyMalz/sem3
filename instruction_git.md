# **Instruction for working with the git version control**

**General information on Git**
![logo](i.webp)

* ## Repository initialization
To initialize the repository you need to enter the command: 
   
    git init
    

* ## Checking the status of a repository
To check the status of the repository you need to enter the command: 

    git status

* ## Fixing changes
I. To commit the changes enter the command: 

    git add _____
 (name of repository, *enter the first letters of the name and press Tab to simplify input*)

II. Then save the new commit:

    git commit -m "_commitname_" 
 
* ## View commit history
To view the commit history enter:

    git log   or  
    git log --oneline --graph
 ( *to display commits compactly* )

* ## Switching between versions
 To switch  between commit versions type:

    git checkout _commitID_ 
( *the first five symbols of the commit ID are sufficient* )

* ## View unconfirmed changes made after the last commit
To view unconfirmed changes enter:

    git diff

* ## Comparing files in two commits
To compare changes in 2 commits enter:

    git diff _1commitID_ _2commitID_
( *the first five symbols of the commit ID are sufficient* )

## Branching
Branching in git allows us to work on different tasks in parallel

* ## Branch list
To display active branches type:

    git branch

* ## Create new Branch
To create new branch enter:

    git branch _name_

* ## Switch branch
To switch branch enter:

    git checkout _branch_name_

* ## Merge Branches
To merge the current branch with another type enter command:

    git merge _namemergebranch_

* ## Unmerged info
To see what information  didn't merge enter command:

    git status

* ## Removal of branches
To delete the branch enter:

    git branch -d _branch_name_
