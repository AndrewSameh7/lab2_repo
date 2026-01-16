![My Image](images\Git_logo.png)

mkdir lab2_repo

cd lab2_repo

git init

touch README.md

git add README.md

git commit -m "initial commit"

git remote add origin git@github.com:AndrewSameh7/lab2_repo.git 

git push origin master

git branch dev

git checkout dev

touch dev.txt

git add dev.txt

git commit -m "add dev file"

git push origin dev

git checkout master

git branch test

git checkout test

touch test.txt

git add test.txt

git commit -m "add test file"

git push origin test

git checkout master

git merge dev

git merge test

git push origin master

git branch -d dev

git branch -d test

git push origin :dev

git push origin :test

git checkout master

git tag -a v1.7 -m "version 1.7"

git push origin v1.7

git push --tags

git tag

git tag -d v1.7

git push origin --delete v1.7

mkdir images

git add README.md images/logo.png

git commit -m "add image to README"

git push origin master
