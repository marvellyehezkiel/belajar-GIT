# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GiT
user@DESKTOP-OD26EJD MINGW64 ~ (master)
$ git config --global user.email marvellps4@gmail.com

user@DESKTOP-OD26EJD MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/user/.git/

user@DESKTOP-OD26EJD MINGW64 ~ (master)
$ cd C:\GIT

user@DESKTOP-OD26EJD MINGW64 /c/GIT
$ git clone https://github.com/marvellyehezkiel/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

user@DESKTOP-OD26EJD MINGW64 /c/GIT
$ ^[[200~git branch
bash: $'\E[200~git': command not found

user@DESKTOP-OD26EJD MINGW64 /c/GIT
$ git branch
fatal: not a git repository (or any of the parent directories): .git

user@DESKTOP-OD26EJD MINGW64 /c/GIT
$ cd belajarGIT

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ ^[[200~git branch Tugas-git
bash: $'\E[200~git': command not found

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-git

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-git
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 4c75518] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[Tugas-git 5eca248] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 4 insertions(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating 2d13fdb..5eca248
Fast-forward
 Tugas-git.txt | 4 ++++
 1 file changed, 4 insertions(+)
 create mode 100644 Tugas-git.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 658 bytes | 329.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/marvellyehezkiel/belajarGIT.git
   2d13fdb..5eca248  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-html

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ touch Tugas-hltm.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt
fatal: pathspec 'Tugas-html.txt' did not match any files

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git reset Tugas-hltm.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git mv Tugas-hltm.txt Tugas-html.txt
fatal: not under version control, source=Tugas-hltm.txt, destination=Tugas-html.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 7475b2b] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ ^[[200~git add Tugas-html.txt
bash: $'\E[200~git': command not found

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html 17a1676] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 2 insertions(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ ^[[200~git checkout main
bash: $'\E[200~git': command not found

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating 5eca248..17a1676
Fast-forward
 Tugas-html.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-html.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 583 bytes | 291.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/marvellyehezkiel/belajarGIT.git
   5eca248..17a1676  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-css

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css dd060e5] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[Tugas-css a0bb42d] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating 17a1676..a0bb42d
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main

Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 654 bytes | 327.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/marvellyehezkiel/belajarGIT.git
   17a1676..a0bb42d  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-js

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 5ac5fe1] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ ^[[200~git commit -m "Menambahkan perubahan pada Tugas-js.txt"
bash: $'\E[200~git': command not found

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt
>
> "
[Tugas-js 483f0ac] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating a0bb42d..483f0ac
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 586 bytes | 586.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/marvellyehezkiel/belajarGIT.git
   a0bb42d..483f0ac  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-midProject

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 8e1ee77] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[Tugas-midProject 2a20af7] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 483f0ac..2a20af7
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 619 bytes | 309.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/marvellyehezkiel/belajarGIT.git
   483f0ac..2a20af7  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-php

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 1008eb1] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php bac4af3] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating 2a20af7..bac4af3
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 559 bytes | 279.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/marvellyehezkiel/belajarGIT.git
   2a20af7..bac4af3  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 45381f6] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[Tugas-finalProject dea765f] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProjeck
merge: Tugas-finalProjeck - not something we can merge

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ ^C

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating bac4af3..dea765f
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
git: 'push origin main' is not a git command. See 'git --help'.

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ ^C

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 630 bytes | 630.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/marvellyehezkiel/belajarGIT.git
   bac4af3..dea765f  main -> main

user@DESKTOP-OD26EJD MINGW64 /c/GIT/belajarGIT (main)
$ git push origin main
