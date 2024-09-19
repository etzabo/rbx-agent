# rbx-agent
## A simple solution to an annoying problem
Although Roblox has updated to allow Windows users to set their FPS limit above 60, the MacOS client is left with no such ability, and the only safe way to modify the client involves adding a configuration file every time the game updates. This repository aims to automate the process through a Launch Agent that utilizes the OS's inbuilt filesystem monitoring capabilities, creating the required configuration file whenever it's removed.
