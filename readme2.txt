# 1- clone the repository you would like to work with.

'git clone <URL-to-repo>'

# 2- navigate to the repository.

'cd <repo-directory>'

# 3- Create a new branch for your changes.

'git checkout -b <branch-name>'

# 4- Make the changes you want to make. 

# 5- When you finished with the changes. add the changes 

'git add <file-name>'

# or 

'git add .     # . to add all the changes'

# 6- commit the changes. here its important to write a description that points to the changes you made. it become easier to search in the commit history. 

'git commit -m  “Description of the changes“ '

# 7- Then push the changes to the branch on Github. 

# git push origin <branch-name>

# if everything ok and the changes is good enogh to overwrite the old version then do 

' git checkout main' 

# and 

' git merge <branch-name> '
