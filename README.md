# 2022-03-08-git_basics

- 'git init' : initialize a repository
	- make sure not a nested repository
- 'git status': show the status of a repository
- 'git add <FILE>': put <FILE> into the staging area
- 'git commit': write a commit + message
- 'git log': shows you the git log / commit history
	- hit "q" to quit if it's too long
	- 'git log --oneline': gives you the shortened oneline version of git log
- 'git diff <HASH> <FILE>'; show you the differences
- 'git diff --staged': show you diff for files in staging area
-  'git checkout <HASH>': take you do <HASH> location
	-'git checkout'---
- 'git checkout <HASH> <FILE>': restore <FILE> from version in <HASH>

## remotes

- 'ssh-keygen': create an ssh key
	-copy your 'id_rsa.pub' into your ssh keys in your account
	- use the SSH url for github, not HTTPS
	
- 'git remote add origin <URL>': set up the remote called origin with <URL>
- 'git remote rm origin' : remote remote (can use this to "rename")

-'git push origin main': sends code from computer to remote
-'git pull origin main': updates local code with remote code
	- technically 'git pull' is 'git fetch' + 'git merge'
- 'git fetch --all': updates history with all remote
	
