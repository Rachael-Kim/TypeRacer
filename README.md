1. Create GitHub repo
2. create new folder
3. run `git init` to create local repo
4. run `npm init -y` to create package.json which is for node.js projects
5. install all the relevant libraries we will be using.
  (Express, postgres (pg), pg-hstore, sequelize)
6. create .gitignore file. (node_modules do not need to be tracked on github)
7. connect local repo to github repos
 a. `git remote add origin https://github.com/Rachael-Kim/TypeRacer`
 b. git push origin master
8. Create separate branches for different features
 a. git checkout -b branchname
 b. git push origin branchname
9. Create pull request add reviewer
