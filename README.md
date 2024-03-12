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

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~ (master)
$ git config --global user.email "leanzefa@gmail.com"

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~ (master)
$ git init
Reinitialized existing Git repository in C:/Users/Windows 11/.git/

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~ (master)
$ cd desktop

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop (master)
$ git clone https://github.com/Andr011/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
Resolving deltas: 100% (1/1), done.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop (master)
$ git branch

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop (master)
$ git branch Tugas-git
fatal: not a valid object name: 'master'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop (master)
$ git branch Tugas-git
fatal: not a valid object name: 'master'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop (master)
$ cd belajarGIT

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-git

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-git
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-git.txt
error: pathspec 'Tugas-git.txt' did not match any file(s) known to git

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 900ee6b] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ git commit m- "Menambahkan perubahan pada tugas-git.txt"
error: pathspec 'm-' did not match any file(s) known to git
error: pathspec 'Menambahkan perubahan pada tugas-git.txt' did not match any file(s) known to git

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada tugas-git.txt"
[Tugas-git 8a8be17] Menambahkan perubahan pada tugas-git.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git merge Tugas-git
Updating 868c825..8a8be17
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 564 bytes | 282.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Andr011/belajarGIT.git
   868c825..8a8be17  main -> main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-html

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 6a34b84] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html 2eee340] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git merge Tugas-html
Updating 8a8be17..2eee340
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 550 bytes | 275.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Andr011/belajarGIT.git
   8a8be17..2eee340  main -> main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-css

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css ef5016c] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git add tugas-css.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
On branch Tugas-css
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-css.txt

no changes added to commit (use "git add" and/or "git commit -a")

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
On branch Tugas-css
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Tugas-css.txt

no changes added to commit (use "git add" and/or "git commit -a")

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[Tugas-css dc5fcc2] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git merge Tugas-css
Updating 2eee340..dc5fcc2
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 584 bytes | 584.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Andr011/belajarGIT.git
   2eee340..dc5fcc2  main -> main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-js

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 7ea8b25] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[Tugas-js bc2e9a5] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git merge Tugas-js
Updating dc5fcc2..bc2e9a5
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 513 bytes | 513.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Andr011/belajarGIT.git
   dc5fcc2..bc2e9a5  main -> main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-midProject

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 14dbed2] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[Tugas-midProject 8ce4aff] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git merge Tugas-midProject
Updating bc2e9a5..8ce4aff
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 540 bytes | 270.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Andr011/belajarGIT.git
   bc2e9a5..8ce4aff  main -> main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-php

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 6e5d125] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php c269746] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git merge Tugas-php
Updating 8ce4aff..c269746
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 519 bytes | 519.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Andr011/belajarGIT.git
   8ce4aff..c269746  main -> main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch Tugas-finalProject

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject a1a46d4] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[Tugas-finalProject a8e1704] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ git merge Tugas-finalProject
Already up to date.

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$ git push origin main
Everything up-to-date

Windows 11@LAPTOP-KQ67G6CV MINGW64 ~/desktop/belajarGIT (Tugas-finalProject)
$

