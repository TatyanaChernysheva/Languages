# Languages Repositories

…or create a new repository on the command line

echo "# Languages" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/TatyanaChernysheva/Languages.git
git push -u origin main

…or push an existing repository from the command line

git remote add origin https://github.com/TatyanaChernysheva/Languages.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

Добавление информации 
Далее:
git commit -am "Updatefile"
git push -u origin main