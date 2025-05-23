---

## DevOps Lab 1 – Basic Git Commands  
[https://github.com/ShriRadhey-Mishra/Lab-2.git]

In this Lab, we performed and understood the working of some basic Git commands such as:

- `git add <file_name>`: We can add any file specified, or all the files in our Working Directory to the Staging area.  
- `git commit`: After adding our files to the Staging area, we commit those files to the local repository, which we have linked to our remote repository on GitHub.  
- `git push`: Using this command, we push the content of the Local Repository to the remote Repository, where we have our content stored.  
- `git init`: Using this command, we initialize our local working directory as a git Directory. It generates a `.git` directory which helps us to perform git actions in the directory.  
- `git status`: Using this command, we check what is the status of the current branch we are in. We can see what files are added, unstaged, uncommitted etc.  
- `git clone`: We use this command when we are making a clone of a Remote Repository to our local system, where we can make changes to the content.

Using these commands, we can make a directory in our Local machine, initialize it as a git directory, create files in it, add them to the staging area, commit them to the local repository and then create a remote link with the remote repository and push the content to the remote repository.

---

## DevOps Lab 2 – Branching and Merging  
[https://github.com/ShriRadhey-Mishra/Lab-2.git]

In this Lab, we performed and understood working with branches in git, working parallelly with peers, and merging the branches. We performed the experiment in the last repository. We used the following commands:

- `git branch`: We use this command to check what branches we have in our pipeline yet. We can create branches using the syntax, `git branch branch_name`, to create a new branch.  
- `git switch`: We use this command to switch between the branches.  
- `git checkout`: We use this command to check out a specific commit using the commit id which we can get from the `git log --oneline` command. However, using the flag `-b`, we can also create branches using this command using the syntax: `git checkout -b branch_name`.  
- `git merge branch2 branch1`: This command allows us to merge the content of branch2 to branch1. If there is any conflict during merge, it will pop a diff where we can then merge the code manually, resolving the conflict.  
- `git rebase`: Instead of actually merging the branch, we move the base of a branch to the base we desire.

We use these commands to perform a merge, where we make some commits in the main branch, then branch off to a new branch where we make some commits, then merge these branches and resolve the merge conflict.

---
