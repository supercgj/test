Command line instructions

Git global setup
git config --global user.name "某某"
git config --global user.email "mm@mm.com"

Create a new repository
git clone git@gitlab.mm.com:mm-mm/dota.git
cd dota
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Existing folder
cd existing_folder
git init
git remote add origin git@gitlab.mm.com:mm-mm/dota.git
git add .
git commit -m "Initial commit"
git push -u origin master

Existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin git@gitlab.mm.com:mm-mm/dota.git
git push -u origin --all
git push -u origin --tags
