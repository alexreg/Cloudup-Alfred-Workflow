# Cloudup Alfred Workflow

Makes it easy to upload files to [Cloudup](https://cloudup.com/) via Alfred.

## Requirements
The OS X app for Cloudup is __not__ needed for this to work! 
You need [Node.js](http://nodejs.org/download/).

## Usage
Before using it you have to enter your username and password (even if you have the OS X app already installed). Type this in Alfred: `up-config [username] [password]`. 

_Note:_ At the moment you can't have a space in your password. 

![Screenshot 1][screen1]
![Screenshot 2][screen2]
![Screenshot 3][screen3]

## Other stuff
- Your username and token (the password will be exchanged for a token) will be stored on your computer in `~/.cloudup.json`.
- I have included the [official command line tool](https://cloudup.com/blog/share-from-the-command-line-with-up) from Cloudup and have slightly modified it to work for this workflow. 

[screen1]:cloudup-alfred-workflow-action.png
[screen2]:cloudup-alfred-workflow-search.png
[screen3]:cloudup-alfred-workflow-selected.png
