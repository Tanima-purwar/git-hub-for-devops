git init 
   - initializes an empty git repository (it is basically a folder to store code, files etc)
git status
   - Give details about branch, Commits and tracked or untracked files or ay changes done in any file.
   - 
git checkout -b "branch name"
   - to create new branch it will copy all data from master branch just replica of master, So you can test it without affecting original branch.
git checkout "branch name"
   - to move from one branch to another 
git add file name
   - to add file in git or commit a file in git.
git commit -m "added test.py file in git"
   - to pass a message after adding file so that we know why and what we added in git
git restore filename
   - if you made any changes in a file and want to revert just use this command
git restore <file name>
   - restore deleted files.
git restore --staged <file name>
   - used to restore previous status or unstage the file.
git colne <URL of Git repository>
   - It will copy data in your local or you want to add git repository in your system.
git push
   - it will push new file into github repository that you added from local.
git pull
   - it will add new file into local from repository.
git remote add origin <httpp link>
   - To add git repository loation in your local.
git remote set-url origin https://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@github.com/Tanima-purwar/Shell-Scripting-for-DevOps.git
git remote -v
   - To check url of your repository

