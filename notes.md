- stage, commit, push
-Stage: 
    - changes have to be staged
    - what is going on local: 'git status'
    - to stage: 'git add file_name' ( notes.md)
    - to save or commmit: 'git add .' is shortcut above but will change all files in red, it will stage/save everything
    - 'git status' if green everything saved
    -'git commit -m' "Descriptive note about what you did" ex. "Adds notes." in present tense
    - -m tags the message
    - To Recap: 
        - have directory, file.md ( is tracking any changes)
        - 'git add <filename>'
        - save changes: 'git commit -m'
    - This is all local on your computer = local repository

- Commit: 
    - 'git push'
    - 'git remote -v' too see which repos you are attached to
    - "git push origin master' ( origin ) :origin name of repos
    - in github: 
    -  git init
    - git status
    -    git add .  
    - git remote

    - to push to remote: git push origin master



    New Project: 
    -git init  to set stage
    - do code
    - git status: if red not staged, 
    - git add filename or dot, if green
    - git commit -m "message"
    - when done, ready to push to remote: 
    - git remote -v  if nothing there u didn't already make one
    - go to github new repo
    - copy line/url: git remote add origin  url...( only have to do once)
    - paste in terminal 
    -git push origin master

To make changes to repo: 

- git status
- git add . <file_name> ( staging)
- git commit -m "New Message"

- git push origin master



    