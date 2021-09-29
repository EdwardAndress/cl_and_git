# Git

## Workflow

### Starting on the command line
#### Configuration
- Initialize git repo locally
- Create a remote repo
- Configure the local repo to push to the remote repo
  `git add origin <pasted_the_thing_from_github>`

#### Cycling...
1. Do some work
2. Stage the changes to be committed
3. Commit the changes
4. Push the changes

### Starting on Github

### Gotchas

* If there are changes on your remote repo/branch that you do not have locally, you'll need to pull those before you can push anything (on the same branch).

* If you get a merge conflict (where git is unable to discern the correct version of your file/s) you need to open the files in VSCode and either edit them, to manually create the correct version or use the links provided by VSCode to choose one of the two options.  Make sure you remove all the merge conflict markup ('<' and '=').

### Commands

#### init
Initializes git to turn your directory into a local git repo
#### status
Checks the current status of your local repo.
- What has been changed since the last commit?
- What is staged for the next commit?
- What is not staged or not yet tracked?

#### add
Adds a file to the staging area, ready to be included in the next commit

#### commit
Makes a commit (be sure to include -m and your commit message)
If you forget the -m, a text editor will open in your terminal
It's a bit weird but you can get out of it by doing `:wq` then enter
Then you'll need to try again

#### push
Pushes changes from your local repo to your remote repo

#### pull
Pulls changes from your remote repo to your local repo

#### log
Shows a list of all the commits on your local repo

#### remote add origin <repo>
Points your local repo at a remote repo for push and pull

#### remote -v
Shows a list of all the the repo's remote equivalents
