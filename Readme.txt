http://git-scm.com/book


git init  @@ set up repository for a file

git status @@ show the tracking of files

git add [filename] @@ track the [filename]

git add .  @@ add all untracked files

git commit -m '[log]' / git commit => [I] to INSERT => [ESC] => [:wq] to save

touch .gitignore @@ create .gitignore file to specify files and file patterns

git branch [BranchName] @@ create new branch named [BranchName]

git checkout [BranchName] @@ swich to branch [BranchName]

git merge [BranchName] @@ Merge [BranchName]to current Branch

git stash @@ save a unsave changes to come back to apply

git stash apply @@ pop up the previous stash

git remote @@ show a list of remote repositories

git clone [url] @@ copy a [url] end with .git to locally

git remote -v @@ display url of a remote of origin

git fetch origin @@ go out to the server and get any changes made since last cloned or fetched

git pull origin @@ automatically fetch and merge the changes from remote branch to local changes

git push origin master (after git commit) @@ push changes to remote repository known as origin and commit them to the master branch

git remote add [additional repostory] [Url] @@ to add an additional repostory

git push -u origin master (after git commit) @@ push changes to remote repository known as origin and commit them to the master branch

