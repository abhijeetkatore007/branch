# Version: 1.52.0 (user setup)
Commit: 940b5f4bb5fa47866a54529ed759d95d09ee80be
Date: 2020-12-10T22:45:30.502Z
Electron: 9.3.5
Chrome: 83.0.4103.122
Node.js: 12.14.1
V8: 8.3.110.13-electron.0
OS: Windows_NT ia32 10.0.18362



git init
git add .
git status
git push
git remote add origin https://github.
(login sign in etc)


numerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 214 bytes | 214.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abhijeetkatore007/branch.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.


git add .
git commit -m "first commit"                                     
[master (root-commit) f65a047] first commit
 create mode 100644 README.md
git status (master branch)

git checkout -b feature1
Switched to a new branch 'feature1'

git status
On branch feature1
nothing to commit, working tree clean

git push -u origin feature1
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/abhijeetkatore007/branch/pull/new/feature1
remote:
To https://github.com/abhijeetkatore007/branch.git
 * [new branch]      feature1 -> feature1
Branch 'feature1' set up to track remote branch 'feature1' from 'origin'.

git push origin master
Everything up-to-date





*********************************************
 git add .    

 git push     
Everything up-to-date

 git status   
On branch master
Your branch is up to date with 'origin/master'.

 git push     
Everything up-to-date

 git status   
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

 git commit -m"fist commit"
[master 4d64bfc] fist commit
 1 file changed, 2 insertions(+)PS C:\Users\Abhijeet Katore\Documents\New folder\branch> git commit -m"fist commit"
PS C:\Users\Abhijeet Katore\Documents\New folder\branch> git checkout -b feature2
PS C:\Users\Abhijeet Katore\Documents\New folder\branch> git push     
fatal: The current branch feature2 has no upstream branch.
To push the current branch and set the remote as upstream, use        

    git push --set-upstream origin feature2

  git commit --m "changes"
[feature2 5d8754d] changes
 1 file changed, 5 insertions(+), 1 deletion(-)
  git push -u origin feature2 # make changes in online remote repo
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (6/6), 507 bytes | 507.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature2' on GitHub by visiting:   
remote:      https://github.com/abhijeetkatore007/branch/pull/new/feature2
remote:
To https://github.com/abhijeetkatore007/branch.git
 * [new branch]      feature2 -> feature2
Branch 'feature2' set up to track remote branch 'feature2' from 'origin'.
 git push origin master
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abhijeetkatore007/branch.git
   f65a047..4d64bfc  master -> master
 git add .    
[master 39ce4fd] master commit
 1 file changed, 4 insertions(+), 1 deletion(-)
 git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 275 bytes | 275.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abhijeetkatore007/branch.git
   4d64bfc..39ce4fd  master -> master
 git checkout 
feature1
Switched to branch 'feature1'
Your branch is up to date with 'origin/feature1'.
PS C:\Users\Abhijeet Katore\Documents\New folder\branch>
 git add .
 git push -u origin feature1
 git commit -m "faeture1"