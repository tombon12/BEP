# BEP - Destiny 2 Golgoroth Maze Checkpoint bot

Hi all, This is a bot I made in AHK for use in Destiny 2.
(As well as a discord BOT to update the Destiny BOT's status)

I used to host this bot myself, but I am no longer able to.
If you're interested in reading why I stopped hosting the bot, click [here](https://github.com/tombon12/BEP/blob/main/Reasoning.md)

In case anyone wants to take on hosting this bot, feel free to use any of my code.
I have based this bot around a 1920x1080 resolution, so all the button presses will corelate to that resolution.

There's probably many ways that my code can be improved since I'm not at all a good programmer, however this repository is not intended to be used to improve the code, just to share it.

You are free to do whatever you want this code.

If you have any questions about the code feel free to open a question in the Issues tab!

# General Info

Destiny 2 BOT

These files are used for the BOT:

- AFKBot1.AHK & AFKBot2.AHK are basically the same file, once one is completed it opens the other, I used this method because I remotely connected to the PC hosting this bot and then I could edit both files without the need to restart any AHK script, it would use the updates files once either one has finished

- AFKBot3.AHK starts from the HELM, since I use image detection on the top left radar to see when the player is in the HELM, if you ever move the mouse while in the helm, It won't detect the player being in the helm, so AFKBOT3 is for when you are at the helm, have moved the mouse and want to start the script.

- Slots.AHK This file is ran when watching the player slots to detect when players join, when started, it initially sets the player count to 1 and adjusts it until the lobby is full, or the timer kills the script.

- SlotsEmpty.AHK This file is ran once the 7 minute timer has passed and no players have joined, it's the same as slots.ahk except it doesn't set the player count to 1.

Additional Info:
This bot primarely uses image detection for many parts of the script, I have included all the pictures I used, but you will need to take your own screenshots for some of them.

Discord BOT

- Channels.pyw receives commands 

- Updates/Messages.pyw Updates all the servers the discord bot is inside of with the live status.
