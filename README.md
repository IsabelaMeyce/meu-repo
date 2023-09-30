# meu-repo
Atividade Pretalab

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ ls

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ echo Isabela ama sushi> nome-e-comida.txt

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ ls
nome-e-comida.txt

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    IsabelaMeyce.txt
        deleted:    sushi.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        nome-e-comida.txt

no changes added to commit (use "git add" and/or "git commit -a")

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git add nome-e-comida.txt
warning: in the working copy of 'nome-e-comida.txt', LF will be replaced by CRLF the next time Git touches it

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git add nome-e-comida.txt

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git commit -m Isabela ama sushi
error: pathspec 'ama' did not match any file(s) known to git
error: pathspec 'sushi' did not match any file(s) known to git

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git commit -m "Isabela ama sushi"
[master 4cd1aa1] Isabela ama sushi
 1 file changed, 1 insertion(+)
 create mode 100644 nome-e-comida.txt

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git remote add origin https://github.com/IsabelaMeyce/meu-repo.git

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (master)
$ git branch -M main

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (main)
$ git push origin main
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (8/8), 743 bytes | 185.00 KiB/s, done.
Total 8 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/IsabelaMeyce/meu-repo.git
 * [new branch]      main -> main

belam@IsabelaMeyce MINGW32 ~/oficina-git/meu-repo (main)
$

