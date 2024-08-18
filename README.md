nina@LAPTOP-662DV0LT MINGW64 ~ (master)
$ cd learn_git

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ touch third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ touch third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git init
Reinitialized existing Git repository in C:/Users/nina/learn_git/.git/

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git add third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git commit -m "adding third.txt"
[master bd7c9b1] adding third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git log
commit bd7c9b192cc26625745f268ae9b9a1a49605bd6a (HEAD -> master)
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:58:58 2024 +0100

    adding third.txt

commit 39dc09edb3679e23438986d7e6075428252e07dd
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:29:11 2024 +0100

    removing third.txt

commit f5b4978d3e93e0f54570697493d802cd362fb794
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:28:07 2024 +0100

    adding fourth.txt

commit 51a2c5f7ce2195a6bf76ac74220eb6216731a108
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:19:28 2024 +0100

    adding third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ touch fourth.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git add fourth.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git commit -m "adding fourth.txt"
On branch master
nothing to commit, working tree clean

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ rm third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git add .

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git commit -m "removing third.txt"
[master 1a6b7ac] removing third.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git log
commit 1a6b7ac9ecdc64c9dcff7c0f2305ab361c10f2bc (HEAD -> master)
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 21:03:20 2024 +0100

    removing third.txt

commit bd7c9b192cc26625745f268ae9b9a1a49605bd6a
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:58:58 2024 +0100

    adding third.txt

commit 39dc09edb3679e23438986d7e6075428252e07dd
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:29:11 2024 +0100

    removing third.txt

commit f5b4978d3e93e0f54570697493d802cd362fb794
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:28:07 2024 +0100

    adding fourth.txt

commit 51a2c5f7ce2195a6bf76ac74220eb6216731a108
Author: nour-hamdi <nourhamdi78@gmail.com>
Date:   Sun Aug 18 20:19:28 2024 +0100

    adding third.txt

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git config --global core.pager cat

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$ git config --global --list
user.name=nour-hamdi
user.email=nourhamdi78@gmail.com
core.pager=cat

nina@LAPTOP-662DV0LT MINGW64 ~/learn_git (master)
$
