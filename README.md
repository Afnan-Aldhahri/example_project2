mkdir hw2
cd hw2
vi readme.md

Master Bransh:
1.	git init
2.	git add readme.md
3.	git commit   // commit 0
4.	vi readme.md  , git add readme.md
5.	git commit   // commit 1
6.	 vi readme.md  , git add readme.md
7.	git commit   // commit 2
8.	git log 
9.	git checkout cea6e43f17e7a736b96ae67fb8081de810c25746
Bug-Fix Bransh:
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

