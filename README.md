# testrepo
create a new repository on the command line
echo "# testrepo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mailtodheenu/testrepo.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/mailtodheenu/testrepo.git
git branch -M main
git push -u origin main
