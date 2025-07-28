---
title: Handbook Editing
slug: handbook_editing
type: docs
prev: assembly_facilitation
next: handbook
weight: 4
sidebar:
  open: true
---

Editing the handbook is one of the responsibilities of the Process and Strategy Crew 

The following guidelines assume you can find relevant documentation for a range of general tools and processes (e.g., see the resource list below). 

If you would like to contribute and are not yet comfortable with any of the relevant tools and processes, please ask to collaborate on changes and/or request support. 

For updating *content*, this includes: 
* terminal commands
* using git version control processes 
* using markdown syntax to edit documents
* installing and updating software on your local device with terminal commands

For contributing to the *design and maintenance*, additional tools and processes include: 
* the Hextra Starter Template (details below or at https://github.com/imfing/hextra-starter-template)

## Updating content in the Brassica Handbook: 

### Clone the repository
If you've not yet done so: 
1. Open a terminal and navigate to a location on your device where you want to store a copy of this Handbook (e.g.,`cd dev`) and create an approriatly named directory (e.g., `mkdir brassica-collective`) 
2. Retrieve a copy (clone) of the entire handbook repository from the hosted location via URL (e.g. 
`git clone https://github.com/brassica-collective/handbook`)

### Check out a branch for your changes: 
1. Navigate to the location of the cloned handbook repository on your device 
(e.g., `cd /dev/brassica-collective/handbook`)
2. Check status 
(e.g. `git status` or `gst`)
3. Check for any updates (`git pull`)
4. Check-out relevant branch :
    * Check for list of existing branches (`git branch`) - if available, switch to the relevant branch (`git checkout [branch name]`) and check for updates (`git pull`). 
    * If you don't have an existing branch, create one (`git branch [branch name]`)) 
5. Open the branch in the code-editor of your choice 
(e.g.,`code .`)
 
Try to focus on one major change at a time. For each major change, the process is open/create files; edit & preview (until the major change is working), then commit before moving to the next major change. 

### Open or create the document needing an update: 
In your code-editor:
1. Open the file navigation pane
2. Open the markdown (.md) file you want to update 
3. If needed create the file in the relevant folders with appropriate names (all lowercase and using underscores between words, e.g., `conduct_agreement.md`)

### Edit Markdown documents
1. Add/edit the navigation information of title; slug; type; prev; next; etc., (at the top of the file between two sets of ---)
2. Add/edit the file content (using Markdown syntax)

### Preview changes
Preview changes in the front-end (editing the files  as above to fix any broken dependencies)
1. Open a new terminal tab and run the `hugo server` command, this will provide a localhost address 
2. Open the localhost address and navigate to with the relevant section of the website  
3. Check this preview of the website for any broken links, navigation errors, formatting errors, etc.,  

### Review other files for consistency
1. Update the _index.md file in the appropriate folders.
2. Check dependencies in the navigation information of other files 

### Commit changes
In the main terminal window: 
1. check the status of the changes you have made to the branch (`git status`),
2. stage your changes (`git add .`), and 
3. commit your changes with a descriptive message about the major thing you changed (`git commit -m [message]`) 

### Share updates
1. check for any updates by others on the same branch (`git pull`)
2. publish your branch and push your updates 

## Create a pull-request  
In github, you can create a pull-request (so that your changes can be merged into the main branch and deployed): 
1. Select the 'compare and pull request' option
2. Add a title and description for your request
3. Select 'pull request' (request review) 

# Additional Resources:
* Markdown syntax: https://www.markdownguide.org/basic-syntax/  
* Terminal commands for Ubuntu: https://help.ubuntu.com/community/UsingTheTerminal 
* Git commands: https://education.github.com/git-cheat-sheet-education.pdf
* Git Hub explainer: https://docs.github.com/en/get-started/start-your-journey/hello-world 