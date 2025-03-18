# learngit

Full documentation of the git and github:

https://youtu.be/Ez8F0nW6S-w?si=z9lBHBozaAcWKB2e -Apna college
https://youtu.be/q8EevlEpQ2A?si=0k-b_M6B8raa09hQ -chai with code
https://docs.chaicode.com/branches-in-git/

<br>
Author - AUM

    1.git --version <br>
    2.git config -global user.name "username" <br>
    3.git config -global user.email "email" <br>
    4.git config --list <br>

    5.git clone url <!--clone the repo into local machine-->

    <!--General commands-->  cd- to change the directory , ls- to list directories, ls -a : to list all the directories , mkdir - to make a     folder.

    6.git status <!--to check the status of the repo--> untracked, modified, staged, unmodified <br>
    7.git add filename / git add .<!--add the file and the files will the staged to commit--> <br>
    8.git commit -m "message" / git commit -a <!--commit into the github--> <br>
    9.git push origin main <!--to upload the code from the local to github--> <br>
    10.git init <!--to make -git file and keep a track --> <br>

    11.git remote add origin url <!--to add the orinial remote repo --> <br>
    12.git remote -v <!--to check the origin --> <br>
    13.git branch <!--to check the branch --> <br>
    14.git bracnh -M main <!--to change the name into main --> <br>

    15.git push -u origin main <!--to push the rest all to the origin main , basically a shrotcut--><br>

# Git workflow: Github>Clone>changes>add>commit>Push

    16.git checkout -b newbranchname <!--To create new branch--> <br>
    17.git branch -d branchname <!--To cdelete branch--><br>
    18.git checkout branchname <!--To switch branch--> <br>

    19.git diff main <!--comapre and find the differneces--> <br>
    20.git merge main <!--merge with main--> <br>

# pull request - merge the code by checking the version to the main branch in github

    21.git pull origin main <!--To download from the github and match in the local machine--><br>

# resolving the merge conflicts using vscode

# undo changes

# staged changes

    22.git reset filename
    23.git reset

# commited changes

    24.git reset HEAD~1 <!--for one commit--> <b> you can get the hash bu command git log </b>
    25.git reset commithash <!--for particular featuer or stage-->
    26.git reset --hard commithash <!--using hard will edit in the vs code too-->

# fork - rough copy

# Additional info from the chai aur code video:

    27.git log --oneline <!--It shows the short info (useful)-->

    28.git config --global core.editor "code --wait"  <!--To reset git config --global --unset core.editor --> Git will open VS Code to allow you to write a commit message

    29. .gitignore file is created and filename mentioned in those are not tracked , serach also for .gitkeep

    30. Commit (tree) > Tree (blob) > blob  [objects ]

    31.git show -s --pretty=raw <commit-hash>
    32.git ls-tree <tree-id>
    33.git show <blob-id>
    34.git cat-file -p <commit-id>



    35.git branch bug-fix - This command creates a new branch called bug-fix.

    36.git switch bug-fix - This command switches to the bug-fix branch.

    37.git log - This command shows the commit history for the current branch.

    38.git switch -c dark-mode - This command creates a new branch called dark-mode. the -c flag is used to create a new branch.

    39.git stash  

    40.git stash apply

    41.git stash pop

    42.git tag tagname

# reabse concept
    mostly done in the sub branch 

# reflog concept
    full history including commit , rebase, stach etc
    