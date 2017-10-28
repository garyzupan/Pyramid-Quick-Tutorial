export VENV=/home/odroid/projects/quick_tutorial/env
echo $VENV

Hit Ctrl-C twice rapidly to kill WSGI application

How to use Github

https://gethub.com
https://git-scm.com/docs/git-log

cd ~/projects/quick_tutorial
git init
git config --global core.editor vi
git status
git add README.txt
git commit
git diff README.txt
git log
git log --pretty=one-line
git help log
    git checkout -b develop  # create a new branch called develop
    git checkout master
    git merge develop

github.com
Click Plus on upper right > New Repository >
    Repository Name Pyramid Quick Tutorial
    Description Pyramid 1.9.1 Quick Tutorial
    Public
    Do not add .gitignore for ignoring languages
    Do not add a license like GNU
# Push an existing repository from command line
git remote add origin https://github.com/garyzupan/Pyramid-Quick-Tutorial.git
git push -u origin master
