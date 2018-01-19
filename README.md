#howtogithub
---

Actually this file is for my experiment on how to use github
-
#first on github?
follow this etup on your computer
follow this step:
https://help.github.com/articles/set-up-git/

- [ ] download git
- [ ] Set your username in Git
- [ ] Set your commit email address in Git
- [ ] https://help.github.com/articles/caching-your-github-password-in-git/

first of all = open terminal, if you use VScode , there is a built in terminal, use it, by press (for Mac) 
```
control + `
```

than create new folder to store file that you want to you as your new git project

you can use 
```
mkdir blablayournewfoldernamehere
```

than change the directory to there
```
cd blablayournewfoldernamehere
```



create a new repository:
```
curl -u stevchow https://api.github.com/user/repos -d '{ "name": "CSS-Grid-1" }'
```
- [ ] change the stevchow to your github username and cssgrid1 to your new name of repo in github


use HTTPS as clone url, avoid dealing with SSH

```
git init
git remote rm origin
git remote add origin https://github.com/stevchow/XXXXXXXXXXXXChangeMe!.git
git push -u origin master
```
- [ ] change the stevchow to your github username and cssgrid1 to your new name of repo in github

open your new project in VSCode by using
*note, you should still on your new folder in the terminal
```
blablayournewfoldernamehere$ code .
```
code. is for open your new project in new VSCode window, than do you work there


always commit or save before push (update the online repo) by:
```
git commit -am "your-notes-here-what-do-you-want-to-say"
```

after that do push :

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
