# GitBetterTalk

:ok_hand: Repo for talk about Git, Github Pages, and WebRTC

## Git Cheatsheat

* `git checkout -b [branch]` Creates and checks out a branch. 
* `git pull origin [branch]` Pulls changes from actual branch to local branch.
* `git add .` Adds all files - *does not track removed files*
* `git add -u` Adds all files - tracks removed files too
* `git status` Tells you what files are staged
* `git diff HEAD` Tells you what will change when you commit
* `git commit -m "Message"` Commits staged changes with the message "Message"
* `git push origin [branch]` Pushes commit to a branch

## WebRTC Cheatsheat

`channel.connect(channelId)` Connects to an existing WebRTC channel with ID `channelId`
`channel.open(channelId)` Opens a new channel with ID `channelId`
`channel.send(text)` Sends a message with content `text`