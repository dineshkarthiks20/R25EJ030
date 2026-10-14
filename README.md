git config --global user.name "Dinesh Karthik S"
git config --global user.email "ugcet2502755@reva.edu.in"

git init
git add hello.c
git commit -m "Add first C program: Hello World"
git branch -M main
git remote add origin git@github.com:dineshkarthiks20/portfolio_building.git
git push -u origin main

git add README.md
git commit -m "Update README with project details"
git push
