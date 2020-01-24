1. 
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

2. 
commit 5ddf1b17455d6813a0d5a7f39e78f6a595529259 (HEAD -> master, origin/master)
Merge: c40823b b39a29c
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:46:11 2020 -0800

    Merge branch 'greeting'

    Need to bring together all of the files.

commit c40823b369c7832ae387e97daa2fb26ef053ac1a
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:44:59 2020 -0800

    Added readme

commit b39a29c56eb5f97e5210703276260cf2214f5f60 (greeting)
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:28:35 2020 -0800

    Commit on greeting branch

commit 2f4ec5a25d0d9357ca1269376976595d498e97ed
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:00:59 2020 -0800

    first commit

3.
Ran the following command: echo "Hello World" >> helloWorld.txt

4. 
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	./

nothing added to commit but untracked files present (use "git add" to track)

5. Ran command: git add .

6. 
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   basic-commit/helloWorld.txt

7. Ran command: git commit -m "added basic-commits folder with helloWorld.txt file"

8. 
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

9. Ran command: echo "hello world again" >> helloWorld.txt

10. 
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

	modified:   basic-commit/helloWorld.txt

no changes added to commit (use "git add" and/or "git commit -a")

11. Ran command: git add .

12.
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   basic-commit/helloWorld.txt

13. Ran command: echo "hello twice over world" >> helloWorld.txt

14. Ran commands:
	git add .
	git commit -m "changed helloWorld.txt"

15.
Status:
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
Log:
commit 7529db9db99364ff5e6fb97631cf0d817b9fbf2c (HEAD -> master)
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 10:03:48 2020 -0800

    changed helloWorld.txt

commit 9151fa9e609a0cae2d2de0ce6e6dfdbb570f8aec
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 10:00:48 2020 -0800

    added basic-commits folder with helloWorld.txt file

commit 5ddf1b17455d6813a0d5a7f39e78f6a595529259 (origin/master)
Merge: c40823b b39a29c
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:46:11 2020 -0800

    Merge branch 'greeting'

    Need to bring together all of the files.

commit c40823b369c7832ae387e97daa2fb26ef053ac1a
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:44:59 2020 -0800

    Added readme

commit b39a29c56eb5f97e5210703276260cf2214f5f60 (greeting)
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:28:35 2020 -0800

    Commit on greeting branch

commit 2f4ec5a25d0d9357ca1269376976595d498e97ed
Author: Sanjith <sanjith@pacbell.net>
Date:   Fri Jan 24 09:00:59 2020 -0800

    first commit

16. Ran git commit -m "final changes"
	git push -u origin master



