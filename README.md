# proHero


Install git, create GitHub repository

1st - download Git SCM

### **create a new repository on the command line**


echo "# first-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rajib-sadhu/first-repo.git
git push -u origin main


### **push an existing repository from the command line**

git remote add origin https://github.com/rajib-sadhu/first-repo.git
git branch -M main
git push -u origin main