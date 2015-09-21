
#Git command history to build this Repo :

**Note :**
* I wrote also others Mac OSX Terminal (VI editor) just for my info 
* please check the Screenshot-HW2.jpg file in my repo if you want to see my repo visualization by Gitup . I am proud of my repo :) .  

Lets start :

mkdir hw2
cd hw2
vi readme.md

**Master Bransh:**
1.	git init

2.	git add readme.md

3.	git commit   // commit 0

4.	vi readme.md  , git add readme.md

5.	git commit   // commit 1

6.	 vi readme.md  , git add readme.md

7.	git commit   // commit 2

8.	git log 

9.	git checkout cea6e43f17e7a736b96ae67fb8081de810c25746

**Bug-Fix Bransh:**
10.	git checkout -b bug-fix
11.	vi readme.md  , git add readme.md
12.	git commit   // commit 3
13.	vi readme.md  , git add readme.md
14.	git commit   // commit 4
15.	git merge master //there is conflict
16.	vi readme.md //fiexed the conflict , git add readme.md
17.	git commit   // commit 5
18.	vi readme.md  , git add readme.md
19.	git commit   // commit 6
20.	git log
21.	git checkout 535f2349daf823210dea6c5300c0c5db8472b1df
**Bug-Fix-experimental Bransh:**
22.	git checkout -b bug-fix-experimental
23.	vi readme.md  , git add readme.md
24.	git commit   // commit 7
25.	vi readme.md  , git add readme.md
26.	git commit   // commit 8
27.	vi readme.md  , git add readme.md
28.	git commit   // commit 9
29.	git checkout master
**Master Bransh:**
30.	git status
31.	vi readme.md  , git add readme.md
32.	git commit   // commit 10
33.	git checkout bug-fix
Bug-Fix Bransh:
34.	git merge bug-fix-experimental //there is conflict
35.	vi readme.md //fiexed the conflict , git add readme.md
36.	git commit   // commit 11
37.	vi readme.md  , git add readme.md
38.	git commit   // commit 12
39.	git checkout master
40.	git merge bug-fix // Auto merge (commit 13)
41.	vi readme.md  , git add readme.md
42.	git commit   // commit 14


------------------------------------------------
**I was writing these lines while I am working on my Repo :(just for my info) **

*on master:*
add this line for commit 0
add this line for commit 1
add this line for commit 2
add this line for commit 10
add this line after  commit 13
add this line for commit 14

*on bug-fix branch :*
add this line for commit 3
add this line for commit 4 
add this line for commit 5
add this line for commit 6
add this line for commit 11
add this line for commit 12

*on bug-fix-experimental branch :*
add this line for commit 7
add this line for commit 8
add this line for commit 9
-------------------------------------



