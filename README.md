# Github learning pro

## conclusion for git commands  :-

* ### for downloading project from github

``` Shell
git clone "url to github project"
```

* ### to see your state after editing on files :-

``` Shell
git status 
```

***

* ### stages of moving files from your device to remote repo:-

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

* ### for removing files from staging area :-

```shell
git reset -- 'name of file' ,'name of another file '
```

* ### for loading files to local repo :-

``` shell
git commit -am "description"
          or 
git commit -m "description"
```
