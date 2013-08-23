Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/nelsonjava/app.git
git push -u origin master

Push an existing repository from the command line

git remote add origin https://github.com/nelsonjava/app.git
git push -u origin master

Set up git:
  git config --global user.name "Your Name"
  git config --global user.email nelsonjava@gmail.com
