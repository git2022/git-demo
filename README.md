# git demo

git demo repository

## basic git command

 - git init (initialize an empty git repository)
 - git status (show the working tree status)
 - git add (add file contents to the index)
 - git rm (Remove files from the working tree and from the index)
 - git restore (Restore working tree files)
 - git commit (Records the changes to repository)
 - git log (show commit logs)

## git Low Level Commands

 - git cat-file <SHA1>
  * -t (git object type)
  * -s (git object size)
  * -p (git object content)
 - git ls-files 
  * -s (Show staged contents' mode bits, object name and stage number in the output)


## branch

 - git branch (list and branches we have)
 - git branch <branch_name> (create a branch with branch_name, if there already have branch with the name you want to create, it will  - return error)
 - git branch –D <branch_name> (delete branch, can’t delete current active branch or branch not existing)
 - git checkout (change the current active branch)
 - git checkout –b <branch_name> ( checkout a branch, will create that branch if it doesn’t exsit)
 - git branch –m  <old_name> <new_name> (rename branch with new name)


## git remote

- git clone <repository URL>  clone a remote repository to local disk
- git push origin <branch_name> push local branch <branch_name> to remote branch dev, if dev branch does not exist remotely, it would be created.  (--delete to delete a remote branch)
- git remote get remote name
 * -v
 * show origin
- git branch -a  list all branches both local and remote
- git branch -r list all remote branches
- git fetch download objects and refs from remote repository

