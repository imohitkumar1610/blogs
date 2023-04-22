---
title: "20 Git commands you need to learn right NOW!"
datePublished: Fri Apr 07 2023 19:25:37 GMT+0000 (Coordinated Universal Time)
cuid: clg6xsxms000i0ajq9fvg36cc
slug: 20-git-commands-you-need-to-learn-right-now
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1669902107263/nLv7UgP1i.jpg
tags: github, version-control, git

---

**Why do you need to learn Git?**

Git is the most popular **<mark>Version Control system </mark>** and it is being used in all the industries which are out there. It allows you to track the changes you make in your files, so you have a record of what has been done, and you can revert back to specific versions anytime you want.

Here is a rundown of 20 commands that will ease your journey of development and will help you to organise your work. There are more commands available that you can find [here](https://git-scm.com/docs), but these are the most useful and frequent ones that will definitely speed up your coding process.

**1\. git clone:**

it is a command that you can use to clone any git repository to your local system.

```bash
git clone <"repository URL">
```

**2\. git init:**

This command initializes an empty git repository where all the changes and git-related information got saved.

```bash
git init
```

**3\. git status:**

git status command is used to check the status of the git repository and our current project. say which directories git is tracking and which are not.

```bash
git status
```

**4\. git add &lt;fileName&gt;**

git add command is used to add the changes which have been made in the repository, in place of the file name you can add a dot(.) which means add all the changes which have been made.

```bash
git add <fileName>
git add .
git add -A
```

**5\. git commit**

git commit is used to commit the changes which have been added by the git add command.

```bash
git commit -m <"commit message">
```

**6\. git push**

This command is used to push all the changes to the remote repository.

```bash
git push -u origin <origin name>
```

**7\. git remote**

The git remote command lets you **create, view, and delete connections to other repositories**.

```bash
git remote
```

**8\. git remote add origin &lt;URL Of Repository&gt;**

The command `git remote add origin` creates a new remote called Origin located at the URL you provide.

```bash
git remote add origin <URL>
```

**9\. git branch &lt;branch\_name&gt;**

It will create a branch with the name you provide.

```bash
git branch <New_Branch>
```

**10\. git checkout &lt;branch\_name&gt;**

This command helps to switch between multiple branches.

```bash
git checkout <New_Branch>
```

**11\. git checkout -b &lt;New\_Branch&gt;**

This command makes a new branch with the name you provide at the position of New\_Branch and switches to New\_Branch at the same time.

```bash
git checkout -b "Branch_Name"
```

**12\. git config --global user.name "First\_name Last\_Name"**

This command helps to set the user name of the user globally.

```bash
git config --global user.name "user_name"
```

**13\. git config --global user.email "Email\_id"**

It helps the user to set the email id globally.

```bash
git config --global user.email "Email_id"
```

**14\. git pull**

The `git pull` command fetches and downloads content from the remote repository and integrates changes into the local repository.

```bash
git pull 
git pull <remote> <branch>
```

15\. git merge &lt;Branch\_Name&gt;

This command incorporated all the changes to the remote repository which have been made to the local repository.

```bash
git merge <Branch_Name>
```

**16\. git stash**

`git stash` is a built-in command which locally stores all the most recent changes in a workspace and resets the state of the workspace to the prior commit state.

```bash
git stash 
git stash save
```

**17\. git switch**

Quick jumps between branches.

```bash
git switch <Branch_name>
```

**18\. git log**

View the commits, log and branch diagrams\*.\*

```bash
git log
```

**19\. git gc**

Running `git gc` will remove orphaned and inaccessible commits, compress file versions and stored git objects. it optimises the git repository.

```bash
git gc
```

**20\. git instaweb**

Git has a built-in web-based visualiser for browsing local repositories, which lets you view and manage your repo via GUI in Browser.

```bash
git instaweb
```

To open just run `git instaweb` from within your repo. your browser should pop open, and load `http://localhost:1234` .

# **Thank you!**