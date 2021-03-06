# GitCommands

Following are the  Git commands which are being covered:

1. git config
2. git init
3. git clone
4. git add
5. git commit
6. git diff
7. git reset
8. git status
9. git rm
10. git log
11. git show
12. git tag
13. git branch
14. git checkout
15. git merge
16. git remote
17. git push
18. git pull
19. git stash

Git Commands

1. git config
Usage: git config –global user.name “[name]”
Usage: git config –global user.email “[email address]”
cmd-desc: This command sets the author name and email address respectively to be used with your commits.

2. git init
Usage: git init [repository name]
cmd-desc: This command is used to start a new repository.

3. git clone
Usage: git clone [url]
cmd-desc: This command is used to obtain a repository from an existing URL.

4. git add
Usage: git add [file]
cmd-desc: This command adds a file to the staging area.

Usage: git add *
cmd-desc: This command adds one or more to the staging area.

5. git commit
Usage: git commit -m “[ Type in the commit message]”
cmd-desc: This command records or snapshots the file permanently in the version history.

Usage: git commit -a
cmd-desc: This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

6. git diff
Usage: git diff
cmd-desc: This command shows the file differences which are not yet staged.

Usage: git diff –staged
cmd-desc: This command shows the differences between the files in the staging area and the latest version present.

Usage: git diff [first branch] [second branch]
cmd-desc: This command shows the differences between the two branches mentioned.

7. git reset
Usage: git reset [file]
cmd-desc: This command unstages the file, but it preserves the file contents.

Usage: git reset [commit]
cmd-desc: This command undoes all the commits after the specified commit and preserves the changes locally.

Usage: git reset –hard [commit]
cmd-desc: This command discards all history and goes back to the specified commit.

8. git status
Usage: git status
cmd-desc: This command lists all the files that have to be committed.

9. git rm
Usage: git rm [file]
cmd-desc: This command deletes the file from your working directory and stages the deletion.

10. git log
Usage: git log
cmd-desc: This command is used to list the version history for the current branch.

Usage: git log –follow[file]
cmd-desc: This command lists version history for a file, including the renaming of files also.

11. git show
Usage: git show [commit]
cmd-desc: This command shows the metadata and content changes of the specified commit.

12. git tag
Usage: git tag [commitID]
cmd-desc: This command is used to give tags to the specified commit.

13. git branch
Usage: git branch
cmd-desc: This command lists all the local branches in the current repository.

Usage: git branch [branch name]
cmd-desc: This command creates a new branch.

Usage: git branch -d [branch name]
cmd-desc: This command deletes the feature branch.

14. git checkout
Usage: git checkout [branch name]
cmd-desc: This command is used to switch from one branch to another.

Usage: git checkout -b [branch name]
cmd-desc: This command creates a new branch and also switches to it.

15. git merge
Usage: git merge [branch name]
cmd-desc: This command merges the specified branch’s history into the current branch.

16. git remote
Usage: git remote add [variable name] [Remote Server Link]
cmd-desc: This command is used to connect your local repository to the remote server.

17. git push
Usage: git push [variable name] master
cmd-desc: This command sends the committed changes of master branch to your remote repository.

Usage: git push [variable name] [branch]
cmd-desc: This command sends the branch commits to your remote repository.

Usage: git push –all [variable name]
cmd-desc: This command pushes all branches to your remote repository.

Usage: git push [variable name] :[branch name]
cmd-desc: This command deletes a branch on your remote repository.

18. git pull
Usage:  git pull [Repository Link]
cmd-desc: This command fetches and merges changes on the remote server to your working directory.

19. git stash
Usage: git stash save
cmd-desc: This command temporarily stores all the modified tracked files.

Usage: git stash pop
cmd-desc: This command restores the most recently stashed files.

Usage: git stash list
cmd-desc: This command lists all stashed changesets.

Usage: git stash drop
cmd-desc: This command discards the most recently stashed changeset.
