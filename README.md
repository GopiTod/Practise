Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\Windows\abcd\react-dates> cd ..
PS C:\Windows\abcd> ls


    Directory: C:\Windows\abcd


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----       12/14/2018   5:17 PM                abcd
d-----       12/10/2018   7:55 PM                react-dates
-a----       12/10/2018   7:55 PM          39568 DayPicker.jsx


PS C:\Windows\abcd> cd ..
PS C:\Windows> cd ..
PS C:\> ls


    Directory: C:\


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----       12/12/2018  11:29 AM                bananna
d-----        7/14/2018   1:53 PM                ESD
d-----        7/11/2018  10:13 PM                inetpub
d-----        7/11/2018  11:51 AM                Intel
d-----        4/11/2018   4:38 PM                PerfLogs
d-r---       12/10/2018   7:13 PM                Program Files
d-r---        12/3/2018   2:49 PM                Program Files (x86)
d-r---        7/11/2018   9:43 PM                Users
d-----       12/10/2018   7:24 PM                Windows


PS C:\> cd users
PS C:\users> ls


    Directory: C:\users


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----       12/14/2018   5:29 PM                gopi
d-r---       11/21/2018  10:29 AM                Public


PS C:\users> cd .\gopi\
PS C:\users\gopi> cd .\Practise\
PS C:\users\gopi\Practise> git branch
* master
PS C:\users\gopi\Practise> git branch b1
PS C:\users\gopi\Practise> gir status
gir : The term 'gir' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the spelling of the
name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ gir status
+ ~~~
    + CategoryInfo          : ObjectNotFound: (gir:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\users\gopi\Practise> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS C:\users\gopi\Practise> git branch branch1
PS C:\users\gopi\Practise> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS C:\users\gopi\Practise> git branch
  b1
  branch1
* master
PS C:\users\gopi\Practise> git checkout branch1
Switched to branch 'branch1'
PS C:\users\gopi\Practise> git status
On branch branch1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\users\gopi\Practise> git diff
diff --git a/README.md b/README.md
index f56a2e3..94d380a 100644
--- a/README.md
+++ b/README.md
@@ -1,2 +1,5 @@
+git branch
 # Practise
 Git Hub practise
+mnfkjdhfjj
+msnkjhfj
\ No newline at end of file
PS C:\users\gopi\Practise> git add
Nothing specified, nothing added.
Maybe you wanted to say 'git add .'?
PS C:\users\gopi\Practise> git add .
PS C:\users\gopi\Practise> git staus
git: 'staus' is not a git command. See 'git --help'.

The most similar command is
        status
PS C:\users\gopi\Practise> git status
On branch branch1
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.md

PS C:\users\gopi\Practise> git diff
PS C:\users\gopi\Practise> git commit -m "changed 4&5 lines"
[branch1 0b26525] changed 4&5 lines
 1 file changed, 3 insertions(+)
PS C:\users\gopi\Practise> git push
fatal: The current branch branch1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin branch1

PS C:\users\gopi\Practise> git push --set-upstream origin branch1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 300 bytes | 100.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'branch1' on GitHub by visiting:
remote:      https://github.com/GopiTod/Practise/pull/new/branch1
remote:
To https://github.com/GopiTod/Practise.git
 * [new branch]      branch1 -> branch1
Branch 'branch1' set up to track remote branch 'branch1' from 'origin'.
PS C:\users\gopi\Practise> git add .
PS C:\users\gopi\Practise> git commit -m "extre"
[branch1 1f76627] extre
 1 file changed, 2 insertions(+), 2 deletions(-)
PS C:\users\gopi\Practise> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 102.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/GopiTod/Practise.git
   0b26525..1f76627  branch1 -> branch1
PS C:\users\gopi\Practise> history

  Id CommandLine
  -- -----------
   1 cd ..
   2 ls
   3 cd ..
   4 cd ..
   5 ls
   6 cd users
   7 ls
   8 cd .\gopi\
   9 cd .\Practise\
  10 git branch
  11 git branch b1
  12 gir status
  13 git status
  14 git branch branch1
  15 git status
  16 git branch
  17 git checkout branch1
  18 git status
  19 git diff
  20 git add
  21 git add .
  22 git staus
  23 git status
  24 git diff
  25 git commit -m "changed 4&5 lines"
  26 git push
  27 git push --set-upstream origin branch1
  28 git add .
  29 git commit -m "extre"
  30 git push


PS C:\users\gopi\Practise> git add .
PS C:\users\gopi\Practise> git commit -m "extre1"
[branch1 4ae7b18] extre1
 1 file changed, 3 insertions(+), 2 deletions(-)
PS C:\users\gopi\Practise> git push
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (12/12), 1.43 KiB | 132.00 KiB/s, done.
Total 12 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'branch1' on GitHub by visiting:
remote:      https://github.com/GopiTod/Practise/pull/new/branch1
remote:
To https://github.com/GopiTod/Practise.git
 * [new branch]      branch1 -> branch1
PS C:\users\gopi\Practise> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\users\gopi\Practise> git branch branch2
PS C:\users\gopi\Practise> git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
PS C:\users\gopi\Practise> git checkout branch2
Switched to branch 'branch2'
PS C:\users\gopi\Practise> git status
On branch branch2
nothing to commit, working tree clean
PS C:\users\gopi\Practise> git git add .
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init
PS C:\users\gopi\Practise> git add .
PS C:\users\gopi\Practise> git commit -m "add extra"
[branch2 44ce4cb] add extra
 1 file changed, 9 insertions(+), 1 deletion(-)
PS C:\users\gopi\Practise> git push
fatal: The current branch branch2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin branch2

PS C:\users\gopi\Practise> git push --set-upstream origin branch2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 117.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'branch2' on GitHub by visiting:
remote:      https://github.com/GopiTod/Practise/pull/new/branch2
remote:
To https://github.com/GopiTod/Practise.git
 * [new branch]      branch2 -> branch2
Branch 'branch2' set up to track remote branch 'branch2' from 'origin'.
PS C:\users\gopi\Practise> git pull origin/master
fatal: 'origin/master' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
PS C:\users\gopi\Practise> git pull origin master
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), done.
From https://github.com/GopiTod/Practise
 * branch            master     -> FETCH_HEAD
   01357d7..ad8fa19  master     -> origin/master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
PS C:\users\gopi\Practise>  git add .
PS C:\users\gopi\Practise> git commit -m "merge conflict"
[branch2 d78d27b] merge conflict
PS C:\users\gopi\Practise> git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 355 bytes | 88.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/GopiTod/Practise.git
   44ce4cb..d78d27b  branch2 -> branch2
PS C:\users\gopi\Practise>









PS C:\users\gopi\Practise>  history

  Id CommandLine
  -- -----------
   1 cd ..
   2 ls
   3 cd ..
   4 cd ..
   5 ls
   6 cd users
   7 ls
   8 cd .\gopi\
   9 cd .\Practise\
  10 git branch
  11 git branch b1
  12 gir status
  13 git status
  14 git branch branch1
  15 git status
  16 git branch
  17 git checkout branch1
  18 git status
  19 git diff
  20 git add
  21 git add .
  22 git staus
  23 git status
  24 git diff
  25 git commit -m "changed 4&5 lines"
  26 git push
  27 git push --set-upstream origin branch1
  28 git add .
  29 git commit -m "extre"
  30 git push
  31 history
  32 git add .
  33 git commit -m "extre1"
  34 git push
  35 git checkout master
  36 git branch branch2
  37 git status
  38 git checkout branch2
  39 git status
  40 git git add .
  41 git add .
  42 git commit -m "add extra"
  43 git push
  44 git push --set-upstream origin branch2
  45 git pull origin/master
  46 git pull origin master
  47  git add .
  48 git commit -m "merge conflict"
  49 git push





bhdbhiyfgihcwi
dbchiwyfbc
jvuygrfhwkjd
cvbdhvif
ncbvjhf