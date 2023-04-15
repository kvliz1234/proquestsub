# proquestsub
 proquestsub
# GitHub Simple Command II

## Git Clone
`git clone` is used for just downloading exactly what is currently working on the remote server repository and saving it in your machine's folder where that project is placed. (Only one time)

## Git Fetch
`git fetch` just "downloads" the changes from the remote to your local repository. 

## Git Pull
`git pull` is a (clone(download) + merge) operation and mostly used when you are working as teamwork. (Can be multiple time if there is new changes on the repo). git pull downloads the changes and merges them into your current branch. 

## Git Add
`git add` is used to stage the all the file for commit to your local repository by the following command.

## Git Branch
`git branch` is used to see list of available branch on local repository

# To change the remote to ssh

'git remote' set-url origin git@github.com :owner/repository.git

# git config
Usage: git config –global user.name “[name]”
Usage: git config –global user.email “[email address]”
This command sets the author name and email address  respectively to be used with your commits.
# git init
Usage: git init [repository name]
This command is used to start a new repository.
# git clone
Usage: git clone [url]
This command is used to obtain a repository from an existing URL.
# Usage: git add *
This command adds one or more to the staging area.
# git commit
Usage: git commit -m “[ Type in the commit message]”
This command records or snapshots the file permanently in the version history.
Usage: git commit -a
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
# git diff
Usage: git diff
This command shows the file differences which are not yet staged.
Usage: git diff –staged
This command shows the differences between the files in the staging area and the latest version present.
Usage: git diff [first branch] [second branch]
This command shows the differences between the two branches mentioned.
# git reset
Usage: git reset [file]
This command unstages the file, but it preserves the file contents.
Usage: git reset –hard [commit]
This command discards all history and goes back to the specified commit.
# git rm
Usage: git rm [file]
This command deletes the file from your working directory and stages the deletion.
# git log
Usage: git log
This command is used to list the version history for the current branch.
Usage: git log –follow[file]
This command lists version history for a file, including the renaming of files also.
# git show
Usage: git show [commit]
This command shows the metadata and content changes of the specified commit.
# git tag
Usage: git tag [commitID]
This command is used to give tags to the specified commit.
# git branch
Usage: git branch
This command lists all the local branches in the current repository.
Usage: git branch [branch name]
This command creates a new branch.
## Github authentication method
## Plugins

Head to Manage Jenkins > Manage Plugins and install the Github Authentication plugin.

Jenkins will download the plugin, and they'll be available after a restart of Jenkins.

##GitHub Auth Plugin
Head to Manage Jenkins > Configure Global Security.
Under Security Realm, choose "Github Authentication Plugin"
Head to GitHub.com and create an application under the organization (shipping-docker for me) we'll use to authenticate against.
Homepage: http://<server-hostname>
Auth callback url: http://<server-hostname>/securityRealm/finishLogin
Fill in Client ID and Secret








