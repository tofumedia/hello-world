hello-world-testing123
===========
$ mkdir ~/hello-world
# TESTING Creates a directory for your project called "hello-world" in your user directory


$ cd ~/hello-world
# TESTING Changes the current working directory to your newly created directory


$ git init
# Sets up the necessary Git files

# Initialized empty Git repository in /Users/you/hello-world/.git/

$ touch README
# Creates a file called "README" in your hello-world directory

$ git add README
# Stages your README file, adding it to the list of files to be committed


$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"

$ git remote add origin https://github.com/tofumedia/hello-world.git
# Creates a remote named "origin" pointing at your GitHub repo


$ git push origin master
# Sends your commits in the "master" branch to GitHub
