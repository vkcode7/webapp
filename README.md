# webapp
.NET core project for testing pipelines

#### Create a locak webapp and push it to github
Created a webapp project locally using local git
added and committed the files locally
```bash
git add .
git commit "initial commit"
```
Create a github repo by the name of webapp and run the following in bash
git remote add origin https://github.com/vkcode7/webapp.git
```bash
git branch --set-upstream-to=origin/main master
git fetch origin main
git merge --allow-unrelated-histories origin/main
git push origin master:main
```
