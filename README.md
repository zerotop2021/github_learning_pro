# All git commands of github ordered 🔥

## 👍 conclusion for git commands 👍

* ### for downloading project from github 🔽

``` Shell
git clone "url to github project"
```

* ### to see your state after editing on files ⬇️

``` Shell
git status 
```

***

* ### Stages of moving files from your device to remote repo ⬇️

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

* ### for removing files from staging area ⬇️

```shell
git reset -- 'name of file' ,'name of another file '
```

***

* ### for loading files to local repo ⬇️

``` shell
git commit -am "description"
          or 
git commit -m "description"
```

***

* ### to know any branch ⬇️

```sheel
git branch
```

***

* ### to know any remoteRepo ⬇️

```sheel
git remote -v
```

***

* ### to load files to remote Repo ⬇️

```sheel
git push 'remote name' 'branch name' 
git push origin main
```  

* ### how to add Contributors from github  ⬇️

```sheel
     from settings
         options 
             Manage access
                invite a collaborator
```  

***

* ### how to pull updating files from Remote Repo ⬇️

 ```shell

 1] git fetch origin main
 2] git stash save "description"
 3] git merge

 ```

***

* ### how to pull updating files from Remote Repo in one line command ⬇️

``` shell
git pull origin main
````

***

* ### stages of moving files from remote Repo to your device ⬇️

``` shell
remote repo 
     git fetch
        local repo
            git stash save "description"
                staging area
                     git merge
                        working directory
```

***

* ### if you want to erase a file from working directory  ⬇️

```shell
 git  rm  file_name.extention
```

***

* ### to erase a file from both the working directory remote Repo ⬇️

```shell
 1] git rm "file name"
 2] git commit "description"
 3] git push "remote repo name" "branch name"
```

***

* ### if you erased a file from working directory and you want erase it from remote Repo ⬇️

```shell
 1] git add/rm "file name"
 2] git commit "description"
 3] git push "remote repo name" "branch name"
```

***

* ### if you erased a file from working directory by mistake and want to retrieve it ⬇️

```shell
 git restore file_name.extention
```

***

* ### To go back from stage area to working directory ⬇️

```shell
git restore --staged file_name.extension
```

***

* ### To show configuration list ⬇️

```shell
 git config -l
```

***

* ### To show your username and email respectively ⬇️

```shell
git config --global user.email 
git config --global user.name
```

***

* ### To edit your username and email respectively ⬇️

```shell
git config --global user.email "email"
git config --global user.name   "name"
```

***

* ### To edit your username and email respectively another method ⬇️

```shell
git config --global --edit
```

***

* ### To show configration list which related to orgin ⬇️

```shell
git config -l --show origin
```