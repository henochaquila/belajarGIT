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
henoc@LAPTOP-FG8KPOKS MINGW64 ~
$ pwd
/c/Users/henoc

henoc@LAPTOP-FG8KPOKS MINGW64 ~
$ cd PemrogramanWeb

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb
$ cd Tugas

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas
$ git clone https://github.com/henochaquila/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas
$ cd belajarGIT

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git branch Tugas-git

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$  touch Tugas-git.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$  git commit -m "Menambahkan file Tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'henoc@LAPTOP-FG8KPOKS.(none)')

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git config --global user.enail "henoch440@gmail.com"

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git config --global user.name "henochaquila"

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'henoc@LAPTOP-FG8KPOKS.(none)')

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$  git add Tugas-git.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'henoc@LAPTOP-FG8KPOKS.(none)')

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git config --global user.email "henoch440@gmail.com"

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git config --global user.name "henochaquila"

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$  git add Tugas-git.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 3686d3c] Menambahkan file Tugas-git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git merge Tugas-git
Updating 46ea138..3686d3c
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
fatal: A task was canceled.
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/henochaquila/belajarGIT.git/'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/henochaquila/belajarGIT.git
   46ea138..3686d3c  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Everything up-to-date

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$  git branch Tugas-html

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-html)
$  git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html e9b790a] Menambahkan file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git merge Tugas-html
Updating 3686d3c..e9b790a
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 294 bytes | 294.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/henochaquila/belajarGIT.git
   3686d3c..e9b790a  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git branch Tugas-css

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$  git add Tugas-css.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css 027c34e] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-css.txt
Please commit your changes or stash them before you switch branches.
Aborting

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$  git add Tugas-css.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css f4f9712] Menambahkan file Tugas-css.txt
 1 file changed, 1 insertion(+)

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git merge Tugas-css
Updating e9b790a..f4f9712
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 474 bytes | 474.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/henochaquila/belajarGIT.git
   e9b790a..f4f9712  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git branch Tugas-js

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 278f015] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-js)
$  git add Tugas-js.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-js)
$  git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 2d7bd95] Menambahkan file Tugas-js.txt
 1 file changed, 1 insertion(+)

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git merge Tugas-js
Updating f4f9712..2d7bd95
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 466 bytes | 466.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/henochaquila/belajarGIT.git
   f4f9712..2d7bd95  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git branch Tugas-midProject

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$  git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 3b6c7ca] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 2b108a1] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$  git merge Tugas-midProject
Updating 2d7bd95..2b108a1
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 492 bytes | 492.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/henochaquila/belajarGIT.git
   2d7bd95..2b108a1  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git branch Tugas-php

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php ee20d6c] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 08da613] Menambahkan file Tugas-php.txt
 1 file changed, 1 insertion(+)

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git merge Tugas-php
Updating 2b108a1..08da613
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 468 bytes | 468.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/henochaquila/belajarGIT.git
   2b108a1..08da613  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git branch Tugas-finalProject

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$  git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$  git add Tugas-finalProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject d4ea029] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-finalProject.txt
Please commit your changes or stash them before you switch branches.
Aborting

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject 7214057] Menambahkan file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 08da613..7214057
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 543 bytes | 543.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/henochaquila/belajarGIT.git
   08da613..7214057  main -> main

henoc@LAPTOP-FG8KPOKS MINGW64 ~/PemrogramanWeb/Tugas/belajarGIT (main)
$
