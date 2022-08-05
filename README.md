# learngit
## create a new repository on the command line
echo "# xxx" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/AndyQing/xxx.git

git push -u origin master


## push an existing repository from the command line
git remote add origin https://github.com/AndyQing/test.git

git branch -M main

git push -u origin main
