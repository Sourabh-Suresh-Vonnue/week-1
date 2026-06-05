# Git commands

* create repo\
initialize local repo

```
git init
```

or clone existing one.

* clone repo  
```
git clone <URL>
```

* prepare for commit (stage)  
    * one file
    ```
    git add <file>
    ```
    * every file
    ```
    git add .
    ```

* to check status of current branch
```
git status
```

* to commit  
```
git commit -m <message>
```

* to push  
  * main branch
  ```
  git push origin main
  ```
  * branch for first time  
  ```
  git push -u origin <name>
  ```
  * push current branch (already tracking)
  ```
  git push
  ```
* to switch branch  
```
git switch <name>
```
or  
```
git checkout <name>
```