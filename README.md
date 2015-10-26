# GitHub Tutorial

_by John Ruan_

---
## Git vs. GitHub
Although Git and Github are similar to each other in name, they both actually accomplish different tasks. 
Git is used for version control and helps on your local repository, while Github is used for collaboration 
and cloud storage. Github does not require Git to function.

---
## Initial Setup
####Creating a Github account
By creating a github account, you can save your files in the cloud and sharing gets much simpler. This also sets 
you up for transferring/updating your local repository to a remote repository in Github.
####Making a repository on Github
What you will need to do on Github is making a repository with the **same exact name(case-sensitive)** as the file(s)
you are using. Keep in mind that one misplaced character in either repository will cause Github/Git to not recognize
that both of these repo's correlate with each other.
####SSH Keys
SSH stands for "secure shell," and the SSH key is a long "ID" to clone a remote repository into your local machine.
**Every key is unique**, so copying and pasting your key after typing "git clone" in your console will copy your files 
only.
####git config user.name OR user.email
The command in the header shown directly above is to basically "mark this as _your project_." Doing this for 1 time
will mark the repository as yours, so you won't be needing to write it again.

---
## Repository Setup
####"git init"-ing your repository
`git init` will allow you to "initialize" your folder(s)/file(s). What this means is that the file(s) are ready to
be used by other git commands, leading you to be able to upload your file(s) to github.
####"git add", "git commit", and "git push"
`git add` will add the files specified after that command to the "stage," which means the file(s) will be ready to 
be commited. This leads us to `git commit`, which confirms the saves for that file, meaning it is ready to be 
uploaded to github with `git push`. But first, you will need to do this line of code to your repository that you 
want to push  "`git push -u origin master`". What this line does is that it sets up the area you want to push the
files so that simply doing `git push` will push the file(s) into Github.

---
## Workflow & Commands
####Commands
#####Below, you will find a list of commands, and what they do.
* `git init` = command line start
* `git status` = see which files have been edited(red) ; file(s) ready to be committed(green)
* `git add file.txt` = add file(s) to be committed
* `git add .` = adds current directory("." can be replaced with a file name or directory command)
* `git commit -m “short/specific message”` = adding the file to a "confirmed" state
* `git log` = see your past commits
* `git diff` = see differences between versions
* `git push -u origin master`
 * push = send commits from local repo to remote repo
 * -u = “upstream” remembers which remote repo and branch used previously, saves it.

