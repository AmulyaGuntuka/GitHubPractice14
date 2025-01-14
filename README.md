# GitHubPractice14
SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~ (master)
$ git --version
git version 2.47.0.windows.2



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~ (master)
$ cd C:\Users\SRI ADITHYA\OneDrive\Desktop\GitHubPractice
bash: cd: too many arguments



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~ (master)
$ cd OneDrive\Desktop\GitHubPractice
bash: cd: OneDriveDesktopGitHubPractice: No such file or directory



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~ (master)
$ cd Desktop
bash: cd: Desktop: No such file or directory



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~ (master)
$ cd GitHubPractice
bash: cd: GitHubPractice: No such file or directory



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~ (master)
$ cd OneDrive



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive (master)
$ cd Desktop



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop (master)
$ cd GitHubPractice



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git config --global user.name "AmulyaGuntuka"



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ touch prac.html



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ nano prac.html



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ cat prac.html
<!DOCTYPE html>
<html>
<head>
Git Commands
</head>
<body>
<h1>Git Commands</h1>
<p>git config --global user.name "AmukyaGuntuka"</p>
</body>

</html>



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git init
Initialized empty Git repository in C:/Users/SRI ADITHYA/OneDrive/Desktop/GitHubPractice/.git/



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        prac.html

nothing added to commit but untracked files present (use "git add" to track)



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git add prac.html
warning: in the working copy of 'prac.html', LF will be replaced by CRLF the next time Git touches it



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git commit -m "Adding first time"
[master (root-commit) 17e2393] Adding first time
 1 file changed, 11 insertions(+)
 create mode 100644 prac.html



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git status
On branch master
nothing to commit, working tree clean



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git logs
git: 'logs' is not a git command. See 'git --help'.

The most similar command is
        log



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git log
commit 17e239303282e626f90a4db10f07fb56fb217e61 (HEAD -> master)
Author: AmulyaGuntuka <amulyaguntuka@gmail.com>
Date:   Tue Jan 14 10:24:11 2025 +0530

    Adding first time



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git branch
* master



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (master)
$ git branch -m main



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (main)
$ git remote add origin https://github.com/AmulyaGuntuka/GitHubPractice14.git



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (main)
$ git push origin -u main
To https://github.com/AmulyaGuntuka/GitHubPractice14.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/AmulyaGuntuka/GitHubPractice14.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (main)
$ git push origin main
To https://github.com/AmulyaGuntuka/GitHubPractice14.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/AmulyaGuntuka/GitHubPractice14.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (main)
$ git pull https://github.com/AmulyaGuntuka/GitHubPractice14.git
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 873 bytes | 79.00 KiB/s, done.
From https://github.com/AmulyaGuntuka/GitHubPractice14
 * branch            HEAD       -> FETCH_HEAD
fatal: refusing to merge unrelated histories



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (main)
$ git clone https://github.com/AmulyaGuntuka/GitHubPractice14.git
Cloning into 'GitHubPractice14'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (3/3), done.



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice (main)
$ cd GitHubPractice14/



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ touch prac.html



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ nano prac.html



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ cat prac.html
<!DOCTYPE html>
<html>
<head>
Git Commands
</head>
<body>
<h1>Git Commands</h1>
<p>git config --global user.name "AmukyaGuntuka"</p>
</body>

</html>




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        prac.html

nothing added to commit but untracked files present (use "git add" to track)




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git add .
warning: in the working copy of 'prac.html', LF will be replaced by CRLF the next time Git touches it




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git commit -m "First file adding"
[main 60502f6] First file adding
 1 file changed, 11 insertions(+)
 create mode 100644 prac.html




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 399 bytes | 399.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/AmulyaGuntuka/GitHubPractice14.git
   d789c00..60502f6  main -> main



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git branch feature1



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git checkout feature1
Switched to branch 'feature1'



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ touch featureccode,css




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ nano featurecode.css




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ nano featurecode.css




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ cat featurecode.css
body{
 background:cyan;
 align-items:center;
 font-size:20px;
 font-weight:bold;
}



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git merge featurecode
merge: featurecode - not something we can merge




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git merge feature1
Already up to date.



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git push origin main
Everything up-to-date



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git checkout feature1
Switched to branch 'feature1'



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git status
On branch feature1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        featureccode,css
        featurecode.css

nothing added to commit but untracked files present (use "git add" to track)




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ cat featureccode.css
cat: featureccode.css: No such file or directory




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ cat featureccode
cat: featureccode: No such file or directory




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ cat featurecode.css
body{
 background:cyan;
 align-items:center;
 font-size:20px;
 font-weight:bold;
}




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git status
On branch feature1
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        featurecode.css

nothing added to commit but untracked files present (use "git add" to track)




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git add .
warning: in the working copy of 'featurecode.css', LF will be replaced by CRLF the next time Git touches it




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git commit -m "Adding css via branch"
[feature1 23b575a] Adding css via branch
 1 file changed, 6 insertions(+)
 create mode 100644 featurecode.css




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git merge feature1
Updating 60502f6..23b575a
Fast-forward
 featurecode.css | 6 ++++++
 1 file changed, 6 insertions(+)
 create mode 100644 featurecode.css




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 401 bytes | 401.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/AmulyaGuntuka/GitHubPractice14.git
   60502f6..23b575a  main -> main




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git checkout feature1
Switched to branch 'feature1'



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ ls
README.md  featurecode.css  prac.html



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ nano prac.html




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git status
On branch feature1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   prac.html

no changes added to commit (use "git add" and/or "git commit -a")



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git add .
warning: in the working copy of 'prac.html', LF will be replaced by CRLF the next time Git touches it



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git commit -m "modified html via branch"
[feature1 8b3efa8] modified html via branch
 1 file changed, 4 insertions(+)



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (feature1)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.



SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git merge feature1
Updating 23b575a..8b3efa8
Fast-forward
 prac.html | 4 ++++
 1 file changed, 4 insertions(+)




SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 356 bytes | 356.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AmulyaGuntuka/GitHubPractice14.git
   23b575a..8b3efa8  main -> main


SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$ git log
commit 8b3efa85a447cc8c5c4b56872ca96ac6046ec57c (HEAD -> main, origin/main, origin/HEAD, feature1)
Author: AmulyaGuntuka <amulyaguntuka@gmail.com>
Date:   Tue Jan 14 10:54:30 2025 +0530

    modified html via branch

commit 23b575a30eae1fc016093655d846344b7a2c241b
Author: AmulyaGuntuka <amulyaguntuka@gmail.com>
Date:   Tue Jan 14 10:51:25 2025 +0530

    Adding css via branch

commit 60502f6fe20ebe8df355cd03f4391145b09d600a
Author: AmulyaGuntuka <amulyaguntuka@gmail.com>
Date:   Tue Jan 14 10:33:08 2025 +0530

    First file adding

commit d789c00f80e83366c7218cd0c69493426bed19ab
Author: Amulya Guntuka <157285275+AmulyaGuntuka@users.noreply.github.com>
Date:   Tue Jan 14 10:14:30 2025 +0530

    Initial commit

SRI ADITHYA@LAPTOP-RL10NMV3 MINGW64 ~/OneDrive/Desktop/GitHubPractice/GitHubPractice14 (main)
$
