## Setup Git
- git config --global user.name "yourUsername"

- git config --global user.email "yourEmail@gmail.com"

## Change default branch from master to main on new project
- git config --global init.defaultBranch main

## Enables colorfull output
- git config --global color.ui auto

## Sets default branch reconciliation behavior to merging
- git config --global pull.rebase false

## Setup SSH
Generate ad SSH file

- ssh-keygen -t ed25519 -C "yourEmail@gmail.com"

Go on setting on GitHub from the web and go to SSH and GPG keys and create a new SSH

Get the ssh to copy on github

- cat ~/.ssh/id_ed25519.pub

## .gitignore file
It is use to specify the files you don't won't in the repositorie
