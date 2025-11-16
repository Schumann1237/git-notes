# CHAPTER 1 : INTRO TO GIT

## What is Git?
Git is an open-source version control system. You can think of it as another Google Drive, except your files can be stored locally on your own computer. 

## Download Git
You can do it either from the command-line or from downloading the package. The guide to installation can be found on the [website](https://git-scm.com/install/windows).

You can verify your installation on the command-line/terminal by typing `git --version`.

## What is a repository?
A repository is a folder where Git **tracks** all of your files. To create a folder for Git to track, there are some basic steps to follow.
1. Create a folder.
2. Initialise git in the folder.
3. Verify by checking git status.

~~~sh 
mkdir new-folder # create folder for project
cd new-folder # move into folder
git init # initialise git in the folder, making it a git repository
git status # verify git initialisation
~~~
Congratulations, you have just created your first repository!

> Before moving on, note that learning Git should start by learning about the terminal as this helps understanding Git commands and their usages. Only after learning the foundation should a user consider a CLI like Lazygit or its own desktop GUI.

> Another note is that all terminal commands are based on Windows Powershell commands. For LINUX/MAC users, please refer to your own commands.
