CREATE A NEW REPO ON THE CLI
echo "# forgitcmds" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:priiyanshuraj/forgitcmds.git
git push -u origin main

PUSH AN EXISTING REPO FROM CLI
git remote add origin git@github.com:priiyanshuraj/forgitcmds.git
git branch -M main
git push -u origin main