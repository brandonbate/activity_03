# Activity #3

For this activity, you have only to upload your "Meme Encyclopedia App" to this repository. Here is how you do this. In GitBash, navgiate to your projects directory. Run
```
git init .
```
to create a Git repository. Since GitHub uses ```main``` instead of ```master``` for its primary branch, run the following to rename your primary branch:
```
git branch -m master main
```
On this GitHub page, find the http link for this repository. We'll call this ```my_repository_url```. On GitBash, run
```
git remote add origin my_repository_url
```
In order to push to this remote repository, you will need to first pull the repository content (which consists of only this document) into your project folder by running
```
git pull origin main
```
Create a ```.gitignore``` file in your project so that you don't upload your virtual environment or cached files. You can do this by copying the ```.gitignore``` from another project. You then add your project to this repository by running
```
git add .
git commit -m "my submission"
git push -u origin main
```
