# Peerim Anniversary Edition
A modlist for Peeve and Peeverts

Please read this document thoroughly before installing this modlist. If you skip a step, you may encounter errors when you try to run your game. 

This mod is built specifically for Skyrim Anniversary Edition. You must have all creation club content that came with Anniversary Edition installed. Some mods rely on/modify Creation Club content and the game may be unstable if you do not have them. 

**It is strongly advised to start with a fresh install.** If you have mods in your Skyrim folder already, back them up to another folder, then uninstall Skyrim. **Go back to your Skyrim folder and delete any files that remain.** Then reinstall Skyrim and launch it. Configure graphics settings if need be. Get to the main menu and let Skyrim download all the Anniversary Edition Creation Club content. Now you may proceed with downloading and setting up the modlist. 

## Downloading the modlist
This modlist was built using Wabbajack. To install it on your machine, you must first download Wabbajack here: 
https://www.wabbajack.org/

If you are able to, please support the Wabbajack developers on their patreon: 
https://www.patreon.com/user?u=11907933

Once you have Wabbajack installed and the .wabbajack file downloaded from this github, open Wabbajack, and select "install from drive". There are multiple fields here. First, "Target Modlist" should be pointed towards Peerim.wabbajack. "Modlist Installation Location" should be an empty folder. Wabbajack will wipe any files that may be in the folder already, so BE SURE THIS IS AN EMPTY FOLDER. "Resource Download Location" should be filled out by wabbajack automatically. 

Once these are filled out, press the play button. Wabbajack will begin downloading the modlist. A browser window will open and you must click download for each mod (unfortunately the only way to automate this process is to pay for a nexus premium account). 

## Running Mod Organizer 2

In the "Modlist Installation Location" folder, there will be a portable instance of Mod Organizer 2. If you aren't familiar with Mod Organizer 2, the program has tutorials included and there are guides and documentation on their website: https://www.modorganizer.org/

Once you've started this portable instance of Mod Organizer 2 (you may wish to create a shortcut to your desktop, start menu, or pin it to your taskbar), there are few more steps before you can start playing with the modlist. 

## Manually installed mods and other files
A few mods must be manually installed:

Skyrim Script Extender (SKSE64): https://www.nexusmods.com/skyrimspecialedition/mods/30379

SKSE Engine Fixes Part 2: https://www.nexusmods.com/skyrimspecialedition/mods/17230?tab=files&file_id=181171

Install for these mods are simple. You cann follow the installation instructions on nexus, but in short:

Skyrim Script Extender (SKSE64): Open the archive with 7zip or your preferred archive manager. There should be a root folder in the archive, go into this folder if it is present. Take all of the files and folders from this archive and drag and drop them into your Skyrim Special Edition folder on steam. 

SKSE Engine Fixes Part 2: Open the archive with 7zip or your preferred archive manager. Take all of the .dll files from this archive and drag and drop them into your Skyrim Special Edition folder on steam. 

## Final Steps
There are two tools that you must run manually, the Nemesis Behavior Engine and Wrye Bash:  

Project New Reign - Nemesis Behavior Engine: Starting in the directory that the portable instance of MO2 was installed in, this tool is located at "\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe". It is highly recommended to add this .exe to the list of executables MO2 can start for you. 

Once you run Nemesis Behavior Engine, select the following mods; "Book Of Shadows", "True Directional Movement - 360 Horse Archery", "True Directional Movement - Procedural Leaning", "True Directional Movement - Headtracking"; click "Update Engine" and then click "Launch Nemesis Behavior Engine". You may now close Nemesis. 

Before running Wrye Bash, it is **very important** that you sort your plugins. You can either download LOOT (https://loot.github.io/) or sort plugins through Mod Organizer 2 (on the right pane, select "plugins" and then click loot below the tabs on the right). 

You can download the most recent version of Wrye Bash here: https://github.com/wrye-bash/wrye-bash/releases

You must add Wrye Bash to the list of executables Mod Organizer 2 can run and run it through Mod Organizer 2 otherwise Wrye Bash will not be able to see your modlist. At the bottom of your plugin list, Wrye Bash should create a plugin called "Bashed Patch, 0.esp". Right click on this plugin and select "rebuild patch", then click "build patch". This may take a few minutes. 

Once this is done, you should be all set! Make sure you have Skyrim Script Extender (SKSE64) set as an executable and run it through Mod Organizer 2. If you see an abomination on the Skyrim main menu and not the normal logo, you're all set! Happy pissing pvpJug
