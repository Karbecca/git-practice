

```user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git init
Reinitialized existing Git repository in C:/Users/user/OneDrive/Dokumente/The Gym/git_exercise/.git/

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git branch

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git add readme.md

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git commit -m "first commit"
[main (root-commit) 0465a84] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git branch -M main

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git remote add origin https://github.com/Karbecca/git-practice.git

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 205 bytes | 205.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Karbecca/git-practice.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (main)
$ git checkout -b dev
Switched to a new branch 'dev'

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (test)
$ git checkout -
M       readme.md
Switched to branch 'dev'

user@cyberSerpent MINGW64 ~/OneDrive/Dokumente/The Gym/git_exercise (dev)
$ git branch -d test
Deleted branch test (was 0465a84).```





