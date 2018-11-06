# GitHub-Help
Sometimes you just need a little help.

## GitHub 
#### GIT CHEAT SHEET

Git is the open source distributed version control system that facilitates GitHub activities on your laptop or desktop. This cheat sheet summarizes commonly used Git command line instructions for quick reference.

### INSTALL GIT
GitHub provides desktop clients that include a graphical user interface for the most common repository actions and an automatically updating command line edition of Git for advanced scenarios.

#### GitHub for Windows
htps://windows.github.com

#### GitHub for Mac
htps://mac.github.com

Git distributions for Linux and POSIX systems are available on the official Git SCM web site

#### Git for All Platforms
htp://git-scm.com

### CONFIGURE TOOLING
Configure user information for all local repositories

```shell
$ git config --global user.name "[name]"
Sets the name you want atached to your commit transactions
```

```shell
$ git config --global user.email "[email address]"
Sets the email you want atached to your commit transactions
```

```shell
$ git config --global color.ui auto
Enables helpful colorization of command line output
```

### CREATE REPOSITORIES
Start a new repository or obtain one from an existing URL

```shell
$ git init [project-name]
Creates a new local repository with the specified name
```

```shell
$ git clone [url]
Downloads a project and its entire version history
```

### MAKE CHANGES
Review edits and craft a commit transaction

```shell
$ git status
Lists all new or modified files to be commited
```

```shell
$ git diff
Shows file differences not yet staged
```

```shell
$ git add [file]
Snapshots the file in preparation for versioning
```

```shell
$ git diff --staged
Shows file differences between staging and the last file version
```

```shell
$ git reset [file]
Unstages the file, but preserve its contents
```

```shell
$ git commit -m "[descriptive message]"
Records file snapshots permanently in version history
```

### GROUP CHANGES
Name a series of commits and combine completed efforts

```shell
$ git branch
Lists all local branches in the current repository
```

```shell
$ git branch [branch-name]
Creates a new branch
```

```shell
$ git checkout [branch-name]
Switches to the specified branch and updates the working directory
```

```shell
$ git merge [branch]
Combines the specified branch’s history into the current branch
```

```shell
$ git branch -d [branch-name]
Deletes the specified branch
```
