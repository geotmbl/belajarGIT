Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-git

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-git.txt


ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "geotumbel@gmail.com"

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "geotmbl"

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git da7129a] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating df3afa2..da7129a
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

ACER@WojinkY MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 277 bytes | 277.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/geotmbl/belajarGIT.git
   df3afa2..da7129a  main -> main


