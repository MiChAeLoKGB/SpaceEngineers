# SpaceEngineers

## Most useful way of reporting bugs

### Titles

From now on, it would be desirable if new thread titles are made like this: 

[SE Version] - [Location of error] - [Symptom description]

**Example:** [01.028.008] - Client, Host @ WIN7 - Video driver crash (black screen for a few seconds then gets back)

This will make it easier to find the problems for new posters and it helps the mods in the sorting process of the issues.

### Messages

1. always use search function before posting (try not to make duplicates), always take a look at: http://www.spaceengineersgame.com/troubleshooting.html
2. always try to provide exact description of situation in which the bug occurs, best are correct Steps To Reproduce
3. post log file along with description, it can be found here: C:\Users\{YOUR WINDOWS USERNAME}\AppData\Roaming\SpaceEngineers\SpaceEngineers.log
4. post log file to www.pastebin.com and share the link on forum
5. if the crash occurred during Alt+Tabing or the game did not launch at all also attach event viewer log*
6. if the bug is world specific please upload world to Steam workshop or to www.dropbox.com and post the link into the thread
7. if the bug occurs on Dedicated server, please post Dedicated server log along with your normal log, you can find it here: C:\Users\{YOUR WINDOWS USERNAME}\AppData\Roaming\SpaceEngineersDedicated\Default\SpaceEngineers-Dedicated.log



**OBTAINING EVENT VIEWER LOG:**

Please open the Event Viewer (from the start menu, type Event Viewer). In Event Viewer go to Windows Logs, Application and send the top ".NET Runtime" error from Application: SpaceEngineers.exe (see below image) to our support email (top two are enough).
In order to do this right, please follow very carefully these steps:

1. Select the correct file on the left side (Application)
2. Select first the .NET runtime error from top (using default ordering)
3. Copy the large bottom text and send it to our mail or here on forum. Note: make sure that the info is from the Application: SpaceEngineers.exe

**The log file should be from the game session where you've encountered the bug. If you start the game again, the log will be overwritten.

There is also alternative way in case you cannot find your log file:

1. press the start button and 'R' key at the same time
2. paste: %appdata%/SpaceEngineers
3. press enter and you will be redirected straight to the folder where log file is located

THANK YOU!



## Known issues

Hi guys,

a lot of you were currently reporting bugs and we are happy for that. However, there are still issues, that have not been addressed, but we know about them. They are known issues. Therefor we decided to let you guys know which ones we know about, so you do not have to report it. We are doing this for you, so you do not have to search forum far and wide. We also wanted to let you know that these issues have been recognized and they will be dealt with in future.

Thank you for all your reports and time. Your Phand and Lukas. :)

List:

- Landing gears issues: causing shaking, causing torque, desynchronization in MP/DS causing shaking, exploding in MP
- Pistons issues: desynchronization in MP/DS causing explosions, causing rotation of small ships
- Rotors: desynchronization in MP/DS causing explosions, it will tear itself apart on high velocities during turning
- Clipping through ships in MP/DS
- Spotlights and interior lights shining through blocks
- Spotlights light cone misaligned
- Remote control loss in specific conditions
- Interior block edges not deforming properly, causing misaligned textures
- Assembler co-op mode not working properly when ownership is set
- Small ships can pass through closed doors
- Thruster damage not working on cargo container
- Asteroid fragments are damaging ships when drilling
- Turrets are sometimes ignoring enemies
- Player sometimes welds different block then he/she is aiming at
- Connectors not connecting to medical room correctly
- Toolbar items resetting when reloading the game
- Explosion of warheads is not applied correctly on asteroids
- Message about lack of components during welding is showing to everyone on DS
- Text panel writing 'T' during access
- Small-Ship Conveyors and Containers passing Large objects
- Connecting of connectors cause menu freezes
- Can't download mods
- LCD/Text Panel doesn't wrap displayed text
- Projected ships don't have groups
- Join Lag and Slow Downloads
- LOD changing on asteroids
- LODs changing to early for round blocks
- Incorrect reflection of lights in glass blocks
- Window corner is not airtight
- Small cargo container and conveyor are airtight
- Projectors allow duplication of ingots
- Unable to place Warheads in Survival or Creative 
- Dying after taking off helmet in oxygenated environment
- Rotor has a gap between the block and the rotor top part

Also, please check this list if your issue is not already there: https://github.com/MiChAeLoKGB/SpaceEngineers/labels/Bug

**Warning**: this list contains only the biggest problems we know about, so please be merciful when reading it (and judging it :))
