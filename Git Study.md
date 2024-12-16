# __GIT__
Git is a distributed version controll sofware.

Git has 3 steps
- untrack
- tracked
- commited

**How to use**-
1. we need to create a folder/directory
  e.g.
```bash
mkdir myproject
```
2. Initialize the git in this folder/directory

```bash
git init
```
3. check one hidden file created (.git)
```bash
ls -a
```
4. create files
5. check git status
6. Add all file on git track
```bash
git add .
git status
git commit -m "add your message"
git status
git log
git log --oneline
```
**Check the commit details**
```bash
git show e7e996  # Show the details of commit by its  ID
git show HEAD    # It Shows the details of last commit
git show HEAD~1  # It shows the details of 2nd commit from last
```
** Git checkout **
```bash
git checkout 283c7b  # Remove all commit before this commit-ID
git checkout master  # Go to master baranch
git log --oneline
```





