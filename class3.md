# Day 3 Notes
### Date 12-9-20

[Reading - Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Table of Contents
[Vocabulary](#vocabulary)

## Revisions and the Cloud

- Sharing Code
  - Git
  - Github
  
 ## Links
- [Stack overflow - Coding help](https://stackoverflow.com/)
- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
- [Bash Cheat Sheet](https://www.educative.io/blog/bash-shell-command-cheat-sheet)
- [Flip the WEb Bash Cheatsheet](https://github.com/fliptheweb/bash-shortcuts-cheat-sheet)
- [commit best practices](https://github.com/fliptheweb/bash-shortcuts-cheat-sheet)


## Vocabulary
- VCS
- **Git vs Github**
- Local vs remote
- clone
- commit
- **ACP (Add, Commit, Push)**
- deployment
- Working directory - actual directory
- Staging area
- Repository - collection of navigatable history

## Commands
>git status

## What is git
- Version control system
- multiple developers can work on the same code 
  - essential part of saoftware development
- keeps history of changes to your files
  - View, apply, remove changes
- Keep all of your project files in one repository
- it makes collaboration possible

### without version control
- ensures that you don't loose history

### Snapshots in time
- commits represent each succesive version creates a new snapshot on the timeline of the project.
- a new commit creates a new version - retains previous (termpaper->termpaper2->etc)
- squashing will combine the A,B,C but is still a commit in time
- 

### Keeping track
- Each commit has a label that points to it
- HEAD = the label meaninig "You are here"
- You can also assign messages to commits
- messages are like writing a caption for your snapshot (What do you or a collegue want to know 6 months from now)

### Summary of Git
- You can use git to take snap shots of your code at points in time
- git keeps a history
- special lebel - HEAD - means you are here
- usually give a snapshot a label called a message

GitHub
- A hub for a Git repository
- your code in the cloud
- A way to share code with others
- an online palsce to store code (backup is good)
- it uses GIT to help you manage your teams work
  - Version Tracking
  - reviewing changes
  
- git +github = awesome

- git (version control)
- github(online storage hub)
 - open source coding is on Github (tribal knowledge)
 
 Javascript was orginally only allowed to run in a browser.. nodejs allows it to be run on the desktop

## similar products to github
- bitbucket
- aws code commit
- git lab
- assembla (GIT, SVN, Perforce)

gitflow:acp
  - add, commit, push
 - common pattern we will use for git that can be maintained
   - do not want to allow version gaps
>git status
 - git status will not change any files
>code

> git add README.md
 - git add (file name)
 - unstaged changes - adds them to staging area
 
 >git commit -m "Add message to notepad"
 - this will make the snapshot in the history of the project
 - (-m) specifies the messge that will be added to the commit
 
 > git push origin master
- counting objects: 6, done

- this sends any commits (the snapshots of your code) to github
- go to your repo on Github, and look for your files


 
 
 
 
 
 
 
 
 
