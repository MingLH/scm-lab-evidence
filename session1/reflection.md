Q1. Why is a commit history useful when maintaining software? Give one concrete maintenance situation (for example finding when a bug appeared) and refer to your own commits.<br>
A1: It is useful because it record all the history so can revert back if needed. Also it can help to check who is responsidble for the error occur. Lastly, it can help to keep track of all the contributor.

Q2. Explain the difference between Git and GitHub, using your two repositories (the exercise repository and scm-lab-evidence) as examples.<br>
A2: Git is used in local machine while the Github is used for remote access. The exercise repository and scm-lab-evidence have use both git and github. Git track local files change and then push or pull from the Github repo.

Q3. In the GitHub Skills exercise you worked on a branch and used a pull request instead of changing main directly. What risk does this reduce?<br>
A3: Prevent force push. It also gone through a list of check before it is safe to merged. And it can be review first before merge into the main branch

Q4. State which of your commands changed only your computer and which changed GitHub.<br>
A4: git add, git commit, and git pull can only my computer while git push changed Github repo.

Concept Table (Part 1)<br>
Repository: A folder with folders and files in it.<br>
Working Tree: The files that have been edited<br>
Staging area: List of files chosen for the commit<br>
Commit: An immutable cryptographic snapshot<br>
Branch: A movable pointer to a line of commits<br>
Merge: Two branchs combined into one<br>
Remote: A copy of the local repository on the server<br>
Push/Pull/Clone: Upload commits to the remote repo/ Downloading the commits from the remote repo/ Create a copy from a remote repo