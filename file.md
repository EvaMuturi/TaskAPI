
Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   index.js
        new file:   style.css

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   index.js
        modified:   style.css


Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git commit -m "first commit"
[master (root-commit) 03f6cd1] first commit
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 index.js
 create mode 100644 style.css

Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git push original master
fatal: 'original' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ push
bash: push: command not found

Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git remote add origin https://github.com/EvaMuturi/TaskAPI.git

Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 229 bytes | 229.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/EvaMuturi/TaskAPI.git
 * [new branch]      master -> master

Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$ git add file.txt
fatal: pathspec 'file.txt' did not match any files

Eva Muturi@DESKTOP-QHSATQF MINGW64 ~/Downloads/New folder/Task API (master)
$
