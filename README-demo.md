# Git bash snapshot

```bash
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ cd ./

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ cd

PC@DESKTOP-SHIV MINGW64 ~
$ cd d
bash: cd: d: No such file or directory

PC@DESKTOP-SHIV MINGW64 ~
$ cd /d

PC@DESKTOP-SHIV MINGW64 /d
$ cd Full-Stack/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ ls
 Basic-HTML-CSS-projects/   Front-End/                javascript2.0/
 CLI-and-GIT/               frontend-bootcamp-main/   Roadmap.txt
'CSS ChapterWise Notes'/    GIT-demo/                'WebDev Roadmap - Notes.pdf'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cd Basic-HTML-CSS-projects/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/Basic-HTML-CSS-projects (main)
$ ls
 01_QR-Code-Project/          08_Heart-Beating/           15_CSS-Grid-Project/
 02_CatApp/                   09_Stars/                   16_CSS-Grid-area-Project/
 03_YouTube-Hashtag-Header/   10_Wave-Motion-Balls/       Practice/
 04_Preview-Card/             11_Twitter-Card/           'practice float'/
 05_My-Penguin/               12_Cat-Cafe/                README.md
 06_My-Wavy-Penguin/          13_Diwali-Wishes/
 07_Rainbow-Sticks/           14_Practice-CSS-Position/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/Basic-HTML-CSS-projects (main)
$ cd 12_Cat-Cafe/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/Basic-HTML-CSS-projects/12_Cat-Cafe (main)
$ git branch
* main

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/Basic-HTML-CSS-projects/12_Cat-Cafe (main)
$ cd ..

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/Basic-HTML-CSS-projects (main)
$ cd 

PC@DESKTOP-SHIV MINGW64 ~
$ cd /d

PC@DESKTOP-SHIV MINGW64 /d
$ cd Full-Stack/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ ls
 Basic-HTML-CSS-projects/   Front-End/                javascript2.0/
 CLI-and-GIT/               frontend-bootcamp-main/   Roadmap.txt
'CSS ChapterWise Notes'/    GIT-demo/                'WebDev Roadmap - Notes.pdf'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)    
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)    
$ s
bash: s: command not found

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)    
$ ls
about.html  index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)    
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)    
$
 *  History restored 


PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/CLI-and-GIT (main)  
$ ls
index.html  README-CLI.md  script.js
README.md   README-GIT.md  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/CLI-and-GIT (main)  
$ cd 

PC@DESKTOP-SHIV MINGW64 ~
$ cd /d

PC@DESKTOP-SHIV MINGW64 /d
$ cd Full-Stack/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cs GIT-demo/
bash: cs: command not found

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cd GIT-demo/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)   
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)   
$ git branch
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)   
$ bit branch about
bash: bit: command not found

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)   
$ git branch about

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)   
$   git branch
  about
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)   
$ git checkout about
Switched to branch 'about'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)    
$ git branch
* about
  master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)    
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ touch about.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ touch.html
bash: touch.html: command not found

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ ls
about.html  index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git commit -m "create abput/html file"
[about 9bb9fc9] create abput/html file
 1 file changed, 11 insertions(+)
 create mode 100644 about.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ ls
about.html  index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log
commit 9bb9fc93939cbff9d8e4d72abd9434cee7bb781c (HEAD -> about)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 18:30:54 2024 +0530

    create abput/html file

commit facfeea150a79c37a9d61b58e907d0fe6b178ff1 (master)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 18:24:24 2024 +0530

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all
commit 9bb9fc93939cbff9d8e4d72abd9434cee7bb781c (HEAD -> about)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 18:30:54 2024 +0530

    create abput/html file

commit facfeea150a79c37a9d61b58e907d0fe6b178ff1 (master)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 18:24:24 2024 +0530

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all --online
fatal: unrecognized argument: --online

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all --oneline

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)


PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all --oneline
9bb9fc9 (HEAD -> about) create abput/html file
facfeea (master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline
9bb9fc9 (about) create abput/html file
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git checkout master
Switched to branch 'master'


PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline
9bb9fc9 (about) create abput/html file
9bb9fc9 (about) create abput/html file
9bb9fc9 (about) create abput/html file
9bb9fc9 (about) create abput/html file
facfeea (HEAD -> master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git checkout about
Switched to branch 'about'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all --oneline
b97a23b (HEAD -> about) page
9bb9fc9 create abput/html file
facfeea (master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git commit -m "create contact.html file"
[about 4318b9c] create contact.html file
 1 file changed, 12 insertions(+)
 create mode 100644 contacts.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all --oneline
4318b9c (HEAD -> about) create contact.html file
b97a23b page
9bb9fc9 create abput/html file
facfeea (master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout facfeea
Note: switching to 'facfeea'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at facfeea learn

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo ((facfeea...))
$ git log --all --oneline
d01e500 (about) updating about
4318b9c create contact.html file
b97a23b page
9bb9fc9 create abput/html file
facfeea (HEAD, master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo ((facfeea...))
$ git checkout d01e500
Previous HEAD position was facfeea learn
HEAD is now at d01e500 updating about

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo ((d01e500...))
$ git log --all --oneline
d01e500 (HEAD, about) updating about
4318b9c create contact.html file
b97a23b page
9bb9fc9 create abput/html file
facfeea (master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo ((d01e500...))
$ git log --all --oneline
d01e500 (HEAD, about) updating about
4318b9c create contact.html file
b97a23b page
9bb9fc9 create abput/html file
facfeea (master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo ((d01e500...))
$ git log --all --oneline
d01e500 (HEAD, about) updating about
4318b9c create contact.html file
b97a23b page
9bb9fc9 create abput/html file
facfeea (master) learn
2936885 day 14
a6694b1 initial commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo ((d01e500...))
$ cd ..

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cd ..

PC@DESKTOP-SHIV MINGW64 /d
$ mkdir GIT-demo

PC@DESKTOP-SHIV MINGW64 /d
$ ls
'$AV_ASW'/                      'Coding Ninjas'/    'Mern Stack'/    Signature/
'$RECYCLE.BIN'/                  Customization/     'My pic'/        SnakeGame/
 AlldjangoProjects/              desktop.ini         Namaste/        SteamLibrary/
 ApowerRECData/                  DumpStack.log.tmp  'New folder'/    steeleye-solution/
 Articles/                       eclipse/            php/           'System Volume Information'/
 Backup/                         Full-Stack/         Projects/      'vdo cv'/
 Capstone/                       Games/             'python sem8'/   Wallpapers/
 Certificates/                   GIT-demo/           Recovery/      'web Dvelopment'/
'Chai aur Code'/                'Good books'/        Reports/        xampp/
 cloud/                         'java sem8'/         Resume/
 Cloud_Attendance_System-main/   laravel/            Ritik/

PC@DESKTOP-SHIV MINGW64 /d
$ rmdir GIT-demo/

PC@DESKTOP-SHIV MINGW64 /d
$ ls
'$AV_ASW'/                      'Coding Ninjas'/    'My pic'/        SnakeGame/
'$RECYCLE.BIN'/                  Customization/      Namaste/        SteamLibrary/
 AlldjangoProjects/              desktop.ini        'New folder'/    steeleye-solution/
 ApowerRECData/                  DumpStack.log.tmp   php/           'System Volume Information'/
 Articles/                       eclipse/            Projects/      'vdo cv'/
 Backup/                         Full-Stack/        'python sem8'/   Wallpapers/
 Capstone/                       Games/              Recovery/      'web Dvelopment'/
 Certificates/                  'Good books'/        Reports/        xampp/
'Chai aur Code'/                'java sem8'/         Resume/
 cloud/                          laravel/            Ritik/
 Cloud_Attendance_System-main/  'Mern Stack'/        Signature/

PC@DESKTOP-SHIV MINGW64 /d
$ cd Full-Stack/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ ls
 Basic-HTML-CSS-projects/   Front-End/                javascript2.0/
 CLI-and-GIT/               frontend-bootcamp-main/   Roadmap.txt
'CSS ChapterWise Notes'/    GIT-demo/                'WebDev Roadmap - Notes.pdf'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ ls
 Basic-HTML-CSS-projects/  'CSS ChapterWise Notes'/   frontend-bootcamp-main/   Roadmap.txt
 CLI-and-GIT/               Front-End/                javascript2.0/           'WebDev Roadmap - Notes.pdf'   

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ mkdir GIT-demo

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ touch index.html style.css script.js

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ ls
 Basic-HTML-CSS-projects/   Front-End/                index.html       script.js
 CLI-and-GIT/               frontend-bootcamp-main/   javascript2.0/   style.css
'CSS ChapterWise Notes'/    GIT-demo/                 Roadmap.txt     'WebDev Roadmap - Notes.pdf'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cd GIT-demo/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cd GIT-demo/
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack
$ cd GIT-demo/

$ cd GIT-demo/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo
$ touch index.html style.css script.js
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo
$ touch index.html style.css script.js


PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo
PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo
$ git init
Initialized empty Git repository in D:/Full-Stack/GIT-demo/.git/

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ s
bash: s: command not found

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        script.js
        style.css

nothing added to commit but untracked files present (use "git add" to track)

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git commit -m "first commit"
[master (root-commit) b8ff9cf] first commit
 3 files changed, 18 insertions(+)
 create mode 100644 index.html
 create mode 100644 script.js
 create mode 100644 style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all
commit b8ff9cf58d8e1b7e36e1171c5ca54d43c93e22a9 (HEAD -> master)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 19:37:20 2024 +0530

    first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline
b8ff9cf (HEAD -> master) first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch about

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch
  about
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git checkout about
Switched to branch 'about'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git branch
* about
  master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ touch about.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git commit -m "create about.html"
[about 08e7f53] create about.html
 1 file changed, 11 insertions(+)
 create mode 100644 about.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log
commit b8ff9cf58d8e1b7e36e1171c5ca54d43c93e22a9 (HEAD -> master)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 19:37:20 2024 +0530

    first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git status
On branch master
nothing to commit, working tree clean

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch
  about
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log
commit b8ff9cf58d8e1b7e36e1171c5ca54d43c93e22a9 (HEAD -> master)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 19:37:20 2024 +0530

    first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all
commit 08e7f53d22aadf0166722a52e5debe89cc38bace (about)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 19:42:27 2024 +0530

    create about.html

commit b8ff9cf58d8e1b7e36e1171c5ca54d43c93e22a9 (HEAD -> master)
Author: Shiv Shankar Singh <75415783+sh1v-max@users.noreply.github.com>
Date:   Tue Sep 17 19:37:20 2024 +0530

    first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --online
fatal: unrecognized argument: --online

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline
08e7f53 (about) create about.html
b8ff9cf (HEAD -> master) first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --online --graph
fatal: unrecognized argument: --online

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline --graph
* 08e7f53 (about) create about.html
* b8ff9cf (HEAD -> master) first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git commit -m "add learnig para"
[master 93066dd] add learnig para
 1 file changed, 1 insertion(+)

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline --graph
* 93066dd (HEAD -> master) add learnig para
| * 08e7f53 (about) create about.html
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git checkout about
Switched to branch 'about'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git commit -m "change in about branch"
[about d3fcae5] change in about branch
 1 file changed, 1 insertion(+)

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git branch
* about
  master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch
  about
* master

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git branch contact

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline --graph
* d3fcae5 (about) change in about branch
* 08e7f53 create about.html
| * 93066dd (HEAD -> master, contact) add learnig para
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git checkout about
Switched to branch 'about'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git log --all --oneline --graph
* d3fcae5 (HEAD -> about) change in about branch
* 08e7f53 create about.html
| * 93066dd (master, contact) add learnig para
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (about)
$ git checkout contact
Switched to branch 'contact'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (contact)
$ ls
index.html  script.js  style.css

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (contact)
$ touch contact.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (contact)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (contact)
$ git commit -m "add contact.html file"
[contact c0484b8] add contact.html file
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (contact)
$ git log --all --oneline --graph
* c0484b8 (HEAD -> contact) add contact.html file
* 93066dd (master) add learnig para
| * d3fcae5 (about) change in about branch
| * 08e7f53 create about.html
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (contact)
$ git checkout master
Switched to branch 'master'

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git add .

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git commit -m "change index.html file"
[master 9339f0d] change index.html file
 1 file changed, 1 insertion(+)

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline --graph
* 9339f0d (HEAD -> master) change index.html file
| * c0484b8 (contact) add contact.html file
|/
* 93066dd add learnig para
| * d3fcae5 (about) change in about branch
| * 08e7f53 create about.html
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
| * c0484b8 (contact) add contact.html file
|/
* 93066dd add learnig para
| * d3fcae5 (about) change in about branch
| * 08e7f53 create about.html
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git merge contact
Merge made by the 'ort' strategy.
 contact.html | 11 +++++++++++
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --all --oneline --graph
*   62dc9cd (HEAD -> master) Merge branch 'contact'
|\  
| * c0484b8 (contact) add contact.html file
* | 9339f0d change index.html file
|/
* 93066dd add learnig para
| * d3fcae5 (about) change in about branch
| * 08e7f53 create about.html
|/
* b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git merge contact
Already up to date.

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git log --oneline
62dc9cd (HEAD -> master) Merge branch 'contact'
9339f0d change index.html file
c0484b8 (contact) add contact.html file
93066dd add learnig para
b8ff9cf first commit

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$ git merge about
Merge made by the 'ort' strategy.
 about.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)
 create mode 100644 about.html

PC@DESKTOP-SHIV MINGW64 /d/Full-Stack/GIT-demo (master)
$
```