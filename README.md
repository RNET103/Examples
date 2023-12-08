# Proje Dosyasını İndiriniz ` :) `

<br>

## branch `main` olacak



```bash

  git checkout examples-hr-isimsoyisim

```

```bash
  git push origin examples-hr-isimsoyisim
```

- **git fetch --all**: This command fetches updates from all your remotes. It's a good practice to run this before listing branches to ensure you have the latest information from the remote repository.

  ```bash
  git fetch --all
  ```

- **git branch -r**: This command lists all remote branches. The -r flag stands for "remote."

  ```bash
  git branch -r
  ```


Using git switch (Git version 2.23 and newer)
First, check the available branches and see if the branch you want to switch to exists locally:

```bash 
git branch
```
If the branch is already present locally, switch to it:

```bash 
git switch your-branch-name
```
Replace your-branch-name with the name of the branch you want to switch to.

If the branch is not present locally but exists on the remote, you can create a new local branch that tracks the remote branch:

```bash 
git switch -c your-branch-name origin/your-branch-name
```


## Using git checkout (Older versions of Git)


### Check the available branches:

```bash 
git branch
```

### Switch to your branch if it's already present locally:

```bash 
git checkout your-branch-name
```


### If the branch is not present locally but exists on the remote, create and switch to a new local branch that tracks the remote branch:

```bash 
git checkout -b your-branch-name origin/your-branch-name
```
Replace your-branch-name with the actual name of the branch you want to use. This will switch your working directory to the branch you specified, allowing you to work on that branch.

