# All git commands of github ordered 🔥

## 👍 conclusion for git commands 👍

* ### for downloading project from github

``` Shell
git clone "url to github project"
```

* ### to see your state after editing on files :-

``` Shell
git status 
```

***

* ### Stages of moving files from your device to remote repo:-

``` shell
working directory
   git add *  or git add .
     git add 'name of file' 'name of another file '
        staging area
            git commit -am "description"
                local repo
                   git push
                        remote repo 
```

***

* ### for removing files from staging area :-

```shell
git reset -- 'name of file' ,'name of another file '
```

***

* ### for loading files to local repo :-

``` shell
git commit -am "description"
          or 
git commit -m "description"
```

***

* ### to know any branch :-

```sheel
git branch
```

***

* ### to know any remoteRepo :-

```sheel
git remote -v
```

***

* ### to load files to remote Repo :-

```sheel
git push 'remote name' 'branch name' 
git push origin main
```  

* ### how to add Contributor :-

```sheel
     from settings
         options 
             Manage access
                invite a collaborator
```  

***

* ### how to pull updating files from Remote Repo :-

 ```shell

 1] git pull origin main
 2] git stash save "description"
 3] git merge

 ```

***

* ### stages of moving files from remote Repo to your device :-

``` shell
remote repo 
     git pull
        local repo
            git stash save "description"
                staging area
                     git merge
                        working directory
```

***
