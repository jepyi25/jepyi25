ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git
$ git config --global user.email "limpiahoyjohnpaulo_bsit@plmun.edu.ph"

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git
$ ssh-keygen -t rsa -b 4096 -C "limpiahoyjohnpaulo_bsit@plmun.edu.ph"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/ACER/.ssh/id_rsa):
/c/Users/ACER/.ssh/id_rsa already exists.
Overwrite (y/n)? n

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git
$ clip < ~/.ssh/id_rsa.pub

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git
$ ssh -T git@github.com
Hi jepyi25! You've successfully authenticated, but GitHub does not provide shell access.

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git
$ git clone https://github.com/PLMUN-CITCS/advdbms-s01-e01-jepyi25.git
Cloning into 'advdbms-s01-e01-jepyi25'...
remote: Enumerating objects: 17, done.
remote: Total 17 (delta 0), reused 0 (delta 0), pack-reused 17 (from 1)
Receiving objects: 100% (17/17), 6.99 KiB | 311.00 KiB/s, done.
Resolving deltas: 100% (1/1), done.

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git
$ cd advdbms-s01-e01-jepyi25

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git/advdbms-s01-e01-jepyi25 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git/advdbms-s01-e01-jepyi25 (main)
$ git add . HelloWorld.java

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git/advdbms-s01-e01-jepyi25 (main)
$ git commit -m "My first java program"
[main f0191b2] My first java program
 1 file changed, 5 insertions(+)
 create mode 100644 HelloWorld.java

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git/advdbms-s01-e01-jepyi25 (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 403 bytes | 403.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/PLMUN-CITCS/advdbms-s01-e01-jepyi25.git
   c665359..f0191b2  main -> main

ACER@DESKTOP-EPA3GRB MINGW64 ~/Documents/git/advdbms-s01-e01-jepyi25 (main)
$
