# How to use a pull request
## Local repository

1. Clone a repository.
```
$ git clone https://github.com/nishi-hi/pullrequest.git
$ cd pullrequest
```

2. Check current branch.
```
$ git branch -a
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```

3. Create a branch. Start-point is HEAD as default. When you want to use non-HEAD, specify the branch name.
```
$ git checkout -b <branchname> [<start-point>]
Switched to a new branch '<branchname>'
```

4. Check current branch.
```
$ git branch -a
  main
* <branchname>
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```

5. Modify the contents.

6. Add file contents to the index.
```
$ git add .
```

7. Record changes to the repository.
```
$ git commit -m '<message>'
```

8. Update remote repository.
```
$ git push origin <branchname>
```

## Remote repository
1. Click "Compare & pull request" button.

![Compare & pull request button](https://github.com/nishi-hi/pullrequest/blob/main/images/pullrequest_01.png)

2. Edit the message then click "Create pull request" button.

![Create pull request](https://github.com/nishi-hi/pullrequest/blob/main/images/pullrequest_02.png)

3. Examine the difference then click "Merge pull request" button.

![Merge pull request](https://github.com/nishi-hi/pullrequest/blob/main/images/pullrequest_03.png)

4. Edit the message then click "Confirm merge" button.

![Confirm merge](https://github.com/nishi-hi/pullrequest/blob/main/images/pullrequest_04.png)

5. To delete branch after merge, "Delete branch" button.

![Delete branch](https://github.com/nishi-hi/pullrequest/blob/main/images/pullrequest_05.png)
