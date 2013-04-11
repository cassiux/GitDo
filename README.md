GitDo
=======

GitDo is a tool to help newbies (and not) to use GitHub, and is integrated with Growl notification system for Mac OS X.

## Installation

GitDo installation is very simple, just run the following command in your terminal:

`curl -s https://raw.github.com/cassiolupifieri/GitDo/master/bin/git-do > git-do 
; chmod +x git-do ; mv git-do /usr/local/bin`

Now you are ready to use GitDo in your git workflow.

## Commands

Usage:

`git do <command>`

The GitDo commands are:

`help` - List all available commands. 

`growl` - Check if Growl is running, if not start the application.

`create-repo` - Create remote Repository on Github and setup workflow.          

`create-branch`- Create local Branch and move into itself.

`delete-branch` - Delete local Branch and switch to master.

`share` - Make your local Branch available remoteley.

`unshare` - Delete your remote Branch.

`publish` - Create Pull Request direct on Gihub website.

## Growl integration

This script works with Growl notification center, you will need:

- [Growl 1.3+](http://growl.info/) and [Growl notify] (http://growl.info/downloads) to have the notification feature running in your project.
