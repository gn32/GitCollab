### Repository 
*A repository is a storage space. It contains all of the project related files and their file's revision history. Repository canalso be used to discuss, manage and track project's work. Repositories can be owned individually, or can be shared ownership of repositories with other people in an organization.* 
 
### Clone
*Cloning a repository means obtaining a copy of all the File and folder of the project in that repository at that point of time, from GitHub to our local system. This includes the version related files too.*

### Fork
*Creating a fork is producing a personal copy of someone else's project, which means when you fork the copy of the repository you have taken remaining in you GITHub account only. Forks act as a sort of bridge between the original repository and your personal copy.*
 
### Branch  
 *A branch represents an independent line of development. The git branch command lets you create, list, rename, and delete branches. It doesn't let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands.*

### Commit
*The git commit command captures a snapshot of the project's currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to. Commits include lots of metadata in addition to the contents and message, like the author, timestamp, and more.*

### Merge
*Merge is a way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. ... The current branch will be updated to reflect the merge, but the target branch will be completely unaffected.*

### Checkout 
*Checkout is the act of switching between different versions of a target entity. The git checkout command operates upon three distinct entities: files,commits, and branches.*
You can do this with 
**Git checkout <branch_name>**

### Push 
*The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.*
You can do this with 
**Git push -u origin master**

### Pull
*The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. ... Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.*
You can do this with 
**Git pull <branch_url> master**

### Remote Add / Remove / Show
*The git remote command lets you create, view, and delete connections to other repositories. Remote connections are more like bookmarks rather than direct links into other repositories. Instead of providing real-time access to another repository, they serve as convenient names that can be used to reference a not-so-convenient URL.*
You can do this with 
**Git remote add origin <branch_url>.git**

### Status
*The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.*
You can do this with 
**Git status**

### Master branch
*A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.*
