# easy-learn-git

Basics:

Clone a git repo using the command 'git clone <repo_name>'

Delete branches:

Delete local branches using:
'git branch -d <branch_name>'
'git branch -D <branch_name>'

#The -D implies force delete

Delete remote branches using:
'git push <remote_name> --delete <branch_name>


Commit:

Commit using:
'git commit -m <commit_message'

Pull changes using: 

'git pull <remote_name>'

#Note: git pull fetches and merges the code sequencially. Defaults to location pointed by head if <remote_name> is not entered

Fetch changes using:

'git fetch'

#Note Defaults to location pointed by head if <remote_name> is not entered
