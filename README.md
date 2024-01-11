# roblox nextbot respawn
this lua scripts will respawn your bot when falled out of bounds

## installation
- download rbxm file and insert it in your game
  
## configuring
- place "retrypart" into workspace
  - you can move and resize it as you want, but dont rename it
- open "retry" SERVER script in retrypart
  - change humanoid name from "bot" to that one your bot has on line 2
- place "bot_respawn" folder in workspace
  - you can move and add parts in this folder to add bot respawn places
- test it out

## troubleshooting
- problem: **bot_respawn is not a valid member of Workspace "Workspace"**
- solution: make sure bot_respawn folder has "bot_respawn" name and it placed in workspace
  - if it wont work, open "retry" script under "retrypart" and change line 3 to this:
  - ```local spawnfolder = game.Workspace:WaitForChild("bot_respawn")```

- problem: **Attempt to index nil with 'FindFirstChild'...**
  - solution: make sure you correctly changed humanoid name on line 2

## reminder
- example bot not included
- subscribe to my channel

thanks for using, quandie
