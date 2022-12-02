-------------- master ---------------
<br>
git init
<br>
touch FILE.md
<br>
git add FILE.md
<br>
git status
<br>
git commit -m "Commit 0"
<br>
git add FILE.md
<br>
git commit -m "Commit 1"
<br>
git add FILE.md
<br>
git commit -m "Commit 2"
<br>
git log --graph
<br>
git branch bug-fix 6bca515
<br>
git checkout bug-fix 
<br>
-------------- bug-fix -------------
<br>
git add FILE.md
<br>
git commit -m "Commit 3"
<br>
git add FILE.md
<br>
git commit -m "Commit 4"
<br>
git add FILE.md
<br>
git commit -m "Commit 5"
<br>
git checkout master
<br>
-------------- master ---------------
<br>
git merge bug-fix
<br>
git add FILE.md
<br>
git commit -m "Conflicts Fix"
<br>
git checkout bug-fix
<br>
-------------- bug-fix -------------
<br>
git add FILE.md
<br>
git commit -m "Commit 6"
<br>