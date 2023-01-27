# useful git commands:

## configs
- git config --global user.name "YourUserName"
- git config user.name (prints your username)
- git config init.defaultBranch  (check that your branch is main)
- ssh-keygen -t rsa -f ~/.ssh/id_rsa <<< y
- don't set up a password in the next step
- cat ~/.ssh/id_rsa.pub (this generates your new SSH key to add to github)
- go into github to enter this SSH key 
- git init (initialises a new repo)
- git remote add origin <ssh link> 

