…or create a new repository on the command line
echo "# jj" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jiu68229-lgtm/jj.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/jiu68229-lgtm/jj.git
git branch -M main
git push -u origin main