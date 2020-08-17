# The 2020-08-17-git-nbusse 

- `git init`: create git repository in current folder
- `git config -- global user.name "Nicolas Busse"
- `git config -- global user.email "nico.busse@msn.com"

- `git status`: tells you what is going on in your repository
- `git add <FILE>`: Places <FILE> into the staging area
	- `git add README.md`
- `git commit`: commits files in the staging area
	- if you opened this in VI(M): ESC plus `:q!`
	- `git config --global core.editor "nano -w"
- `HEAD`: tells you where you are looking at history
- `git log`: shows you your history 
	-`git log --oneline`: shows you the first line of the ID for each change
- `git diff`: shows your current state with last known state differences
	-  `git diff --staged`: shows difference from staging area with last known
	- you can use `git log --oneline` to specifiy different versions in histroy
- `git commit -m "MESSAGE": allos you to type a message in a one line 
- `git remote add origin <url>`: adds URL with the name origin
- `git push origin master`: pushes master branch to the origin remote
- `git pull origin master`: pulls the master branch from origin to local computer

- Modified line from github!
Asdasdasd

- You can make changes to different parts of a file and it will be combined automatically
- Look for the >>> and <<<< lines, and fix those lines to what you want to keep

This line is to make your life more complicated. Regards <3
