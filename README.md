# fff
13215@DESKTOP-3LL9C40 MINGW64 ~/Desktop (master)
$ cd E:\gitr

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr
$ ls
aaaa.txt

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr
$ git init
Initialized empty Git repository in E:/gitr/.git/

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$ git add aaaa.txt

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$ git commit -m "first commit"
[master (root-commit) 3160a14] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 aaaa.txt

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$ git branch -M master

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$ git remote add origin https://github.com/smallzqq-cloud/fff.git

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$ git push -u origin master
fatal: HttpRequestException encountered.
   ▒▒▒▒▒▒▒▒ʱ▒▒▒▒
error: unable to read askpass response from 'D:/Git/mingw64/libexec/git-core/git-gui--askpass'
Password for 'https://smallzqq-cloud@github.com':

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 211 bytes | 211.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/smallzqq-cloud/fff.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

13215@DESKTOP-3LL9C40 MINGW64 /e/gitr (master)
$

