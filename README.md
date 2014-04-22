Steps-to-Remember
=================
First make a repository in github<br>
In gitbash:<br>
pwd ...to see current working directory<br>
cd  /c/users/user.name/document/etc ...to go to the local directory that I want to use git with<br>
git init ...to initialize a local git repository in the local working directory<br>
git remote add origin https://github.com/username/reponame.git ... to point the local repo at the github repo<br>
git pull origin master ...to fetch the github repo stuff first<br>
git add . ...to add all local working directory files to local git repo, which was just pulled from github<br>
git commit -m "notes about this commit" ...to commit files or changes to local repo<br>
git push ...to push the local repo commit to github<br><br>


mkdir ~/examplereponame ...to make a local folder in my working directory for the same name as the repo, if needed<br>
git clone https://github.com/username/reponame.git ...to copy the github repo to local working directory, if needed. This can replace git init and git remote (I think)<br>
