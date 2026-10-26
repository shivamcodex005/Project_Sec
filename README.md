Microsoft Windows [Version 10.0.22631.6199]
(c) Microsoft Corporation. All rights reserved.

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git init
Initialized empty Git repository in C:/Users/hp/Desktop/Shivam SEC/Project_Sec/.git/
alue>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git -- version
unknown option: --
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git --version
git version 2.45.2.windows.1

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git --version
git version 2.45.2.windows.1

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git config --local user.name "Shivam"

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git config --local user.email "jbshivam2367@gmail.com"

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>mkdir mca-git-lab

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git init
Reinitialized existing Git repository in C:/Users/hp/Desktop/Shivam SEC/Project_Sec/.git/

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git version
git version 2.45.2.windows.1

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        p.html

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git init
Reinitialized existing Git repository in C:/Users/hp/Desktop/Shivam SEC/Project_Sec/.git/

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        p.html

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git add p.html

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git add Readme,md
fatal: pathspec 'Readme,md' did not match any files

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git add ,
fatal: pathspec ',' did not match any files

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git add .

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   p.html


C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   p.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)   
        README.md


C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git add .  

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git add .

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git status        
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   p.html


C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git commit -m "We have this file"  
[master (root-commit) 55371b8] We have this file
 2 files changed, 15 insertions(+)
 create mode 100644 README.md
 create mode 100644 p.html

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git status              
On branch master
nothing to commit, working tree clean

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git remote add origin https://github.com/shivamcodex005/Project_Sec.git

C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git branch -M main      
                                           
C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 20 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 417 bytes | 417.00 KiB/s, done.       
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)      
To https://github.com/shivamcodex005/Project_Sec.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.


C:\Users\hp\Desktop\Shivam SEC\Project_Sec>git pull  origin main
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (6/6), done.
remote: Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 2.22 KiB | 84.00 KiB/s, done.
From https://github.com/shivamcodex005/Project_Sec
 * branch            main       -> FETCH_HEAD
   55371b8..1328e28  main       -> origin/main
Updating 55371b8..1328e28
Fast-forward
 README.md | 18 ++++++++++++++++++
 1 file changed, 18 insertions(+)
