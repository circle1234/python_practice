mkdir ~/python_practice
# Creates a directory for your project called "python_practice" in your user directory

cd ~/python_practice
# Changes the current working directory to your newly created directory

git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/python_practice/.git/

touch README
# Creates a file called "README" in your python_practice directory

git add README
# Stages your README file, adding it to the list of files to be committed

git commit -m 'first commit'
# Commits your files, adding the message "first commit"

git remote add origin https://github.com/circle1234/python_practice.git
# Creates a remote named "origin" pointing at your GitHub repository

git push origin master
# Sends your commits in the "master" branch to GitHub
