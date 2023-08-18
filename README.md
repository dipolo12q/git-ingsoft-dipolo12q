# git-ingsoft-dipolo12q

# Integrantes
## 1.Nincol Abraham Quiroz Maquin
## 2.Franco Matias Pacheco Espino

# Comandos consola integrante 1:

PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch
* master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch feature1
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch
  feature1
* master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature1
Switched to branch 'feature1'
M       app.py
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch
* feature1
  master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git status
On branch feature1
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   app.py

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git add app.py
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git commit -m "cambio en feature1"
[feature1 43012c0] cambio en feature1
 1 file changed, 17 insertions(+)
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout master  
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature1
Switched to branch 'feature1'
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature1
Switched to branch 'feature1'
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout master  
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git add app.py
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git commit -m "Master"            
[master 77decd7] Master
 1 file changed, 17 insertions(+)
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 351 bytes | 351.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/dipolo12q/git-ingsoft-dipolo12q
   ef0f9d4..77decd7  master -> master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature1
Switched to branch 'feature1'
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push
fatal: The current branch feature1 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature1

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push --set-upstream origin feature1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 371 bytes | 371.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'feature1' on GitHub by visiting:
remote:      https://github.com/dipolo12q/git-ingsoft-dipolo12q/pull/new/feature1
remote:
To https://github.com/dipolo12q/git-ingsoft-dipolo12q
 * [new branch]      feature1 -> feature1
branch 'feature1' set up to track 'origin/feature1'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git status
On branch feature1
Your branch is up to date with 'origin/feature1'.

nothing to commit, working tree clean
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch
* feature1
  master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout master   
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 373 bytes | 31.00 KiB/s, done.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git pull
fatal: refusing to merge unrelated histories
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git merge --allow-unrelated-histories
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 648 bytes | 648.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
remote: Bypassed rule violations for refs/heads/master:
remote:
remote: - Changes must be made through a pull request.
remote:
To https://github.com/dipolo12q/git-ingsoft-dipolo12q
   bc2f14a..8247b46  master -> master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push                               
Everything up-to-date
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch feature3
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature1
Switched to branch 'feature1'
Your branch is up to date with 'origin/feature1'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature3
Switched to branch 'feature3'
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push
fatal: The current branch feature3 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature3

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push --set-upstream origin feature3
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'feature3' on GitHub by visiting:
remote:      https://github.com/dipolo12q/git-ingsoft-dipolo12q/pull/new/feature3
remote:
To https://github.com/dipolo12q/git-ingsoft-dipolo12q
 * [new branch]      feature3 -> feature3
branch 'feature3' set up to track 'origin/feature3'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push
Everything up-to-date
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout feature1
Switched to branch 'feature1'
Your branch is up to date with 'origin/feature1'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch
* feature1
  feature3
  master
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git push
Everything up-to-date
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git commit -m "modificación nincol feature1"
On branch feature1
Your branch is up to date with 'origin/feature1'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   app.py

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git add app.py
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git commit -m "modificación nincol feature1"
[feature1 96b79ec] modificación nincol feature1
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\ninco\Documents\2023-2\IS\git-ingsoft-dipolo12q> git branch
  feature1
  feature3
* master

# Comandos Consola Integrante 2

git clone https://github.com/dipolo12q/git-ingsoft-dipolo12q.git
git branch feature2
git checkout feature2
git add app.py
git commit -m “Mi modificacion”
git status
git push --set-upstream origin feature2






# Comentario

Los merge al feature 3 y resolución de pull request/conflictos se hicieron por la pag web de github, se pueden consultar las modificiones ahí.