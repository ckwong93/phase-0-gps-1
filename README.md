# phase-0-gps-1

Last login: Tue Apr 19 17:43:02 on ttys000
[~] ruby-2.2.1 $ git clone https://github.com/ckwong93/phase-0-gps-1.git
Cloning into 'phase-0-gps-1'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
Checking connectivity... done.
[~] ruby-2.2.1 $ touch awesome_page.md
[~] ruby-2.2.1 $ git add awesome_page.md
fatal: Not a git repository (or any of the parent directories): .git
[~] ruby-2.2.1 $ git init
Initialized empty Git repository in /Users/macbook/.git/
[~] ruby-2.2.1 $ git add awesome_page.md
[~] ruby-2.2.1 $ git commit -m "Add the awesome page"
[master (root-commit) 03f1fc0] Add the awesome page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 awesome_page.md
[~] ruby-2.2.1 $ git push origin master
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
[~] ruby-2.2.1 $ pwd
/Users/macbook
[~] ruby-2.2.1 $ ls
Applications    Downloads       Music           awesome_page.md mac             practice-repo
Desktop         Library         Pictures        dotfiles        myapp           railsbridge
Documents       Movies          Public          laptop.log      phase-0-gps-1
[~] ruby-2.2.1 $ cd phase-0-gps-1
[~/phase-0-gps-1] ruby-2.2.1 $ touch awesome_page.md
[~/phase-0-gps-1] ruby-2.2.1 $ git add awesome_page.md
[~/phase-0-gps-1] ruby-2.2.1 $ git commit -m "Add awesome_page"
[master 1fdd402] Add awesome_page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 awesome_page.md
[~/phase-0-gps-1] ruby-2.2.1 $ git push origin master
Username for 'https://github.com': ckwong93
Password for 'https://ckwong93@github.com': 
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/ckwong93/phase-0-gps-1.git
   e836381..1fdd402  master -> master
[~/phase-0-gps-1] ruby-2.2.1 $ git checkout -b add-command-log
Switched to a new branch 'add-command-log'
[~/phase-0-gps-1] ruby-2.2.1 $ subl README.md
[~/phase-0-gps-1] ruby-2.2.1 $ 


Clone- copy the repository from online github
Touch- created the markdown file
add- prepping for commit
commit- save a checkpoint 
push- saving the changes to github
checkout -b - create a new branch
sublime - open the Readme.md




