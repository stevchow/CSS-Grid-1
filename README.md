#howtogithub

Actually this file is for my experiment on how to use github
first on github?
follow this etup on your computer
follow this step:
https://help.github.com/articles/set-up-git/

- [ ] download git
- [ ] Set your username in Git
- [ ] Set your commit email address in Git
- [ ] https://help.github.com/articles/caching-your-github-password-in-git/

create a new repository:
```
curl -u stevchow https://api.github.com/user/repos -d '{ "name": "CSS-Grid-1" }'
```
- [ ] change the stevchow to your github username and cssgrid1 to your new name of repo in github


use HTTPS as clone url, avoid dealing with SSH

```
echo "# CSS-Grid-1" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote rm origin
git remote add origin https://github.com/stevchow/CSS-Grid-1.git
git push -u origin master
```
- [ ] change the stevchow to your github username and cssgrid1 to your new name of repo in github

always commit or save before push (update the online repo) by
git commit -am "your-notes-here-what-do-you-want-to-say"

than

```
git push
```


stay update with online project:
```
git pull
```


if you already have repo in github, clone it / bring it to your machine by this command:
```
git clone https://github.com/username/target-project.git
```
