# How to check out commits (i.e. view the history of a repo)

## Step 1

- Open up your terminal
- Go (`cd`) to the folder where you want to put the repo
- Clone the repo from github to your computer with the following commands

```bash
cd path/to/folder
git clone <url>
```

⚠️ **Replace `path/to/folder` with the actually path**
⚠️ **Replace `<url>` with the actually github link**

## Step 2

- Go(`cd`) to the repo
- Look up the commit history

```bash
cd path/to/repo
git log
```

⚠️ **Replace `path/to/repo` with the actually path**

Now you should see a list of commits,

- Use arrow key to go up or down
- Type `q` to quit the viewing mode

## Step 3

- Before you quit viewing the commits, copy (`Command + c (Mac) / Ctrl + c (Windows)`) one of the commit ids(the long random string after `commit:`) that you want to check out. Then quit the viewing mode.

- Use the following command to go to a particular commit

```bash
git checkout <commit id>
# Example
git checkout 1234567890
```

⚠️ **Replace the `<commit id>` with the actually commit id you just copied.**

## Step 4

- Use VS Code to open the folder to see the content of the folder

- You will see that the folder is at the state of that commit

## Step 5

- Go back to the current state (the latest version of the folder)

```bash
git checkout master
```
