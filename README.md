mkdir ~/python_practice


cd ~/python_practice


git init

touch README


git add README.txt

$ git status

git commit -m 'first commit'

$ git add '*.txt'

git remote add origin https://github.com/username/python_practice.git

$ git push -u origin master

$ git pull origin master

$ git diff HEAD

$ git add task/code.txt

$ git diff --staged

$ git checkout -- task.txt

$ git branch clean_up

$ git checkout clean_up

$ git rm '*.txt'

$ git commit -m "Remove code"

$ git checkout master

$ git merge clean_up

$ git branch -d clean_up

$ git push

