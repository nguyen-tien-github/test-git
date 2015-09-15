echo "# test-git" >> README.md
git init
git add README.txt
git commit -m "first commit"
git remote add origin https://github.com/nguyen-tien-mulodo/test-git.git
git push -u origin master

…or push an existing repository from the command line
test

git remote add origin https://github.com/nguyen-tien-mulodo/test-git.git
git push -u origin master
…or import code from another repository

You can init this repository with code from a Subversion, Mercurial, or TFS project.

