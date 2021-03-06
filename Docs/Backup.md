# Backing up UltSky: 
1)  Back up the main UltSky folder - the one with ModOrganizer.exe from which you start the game.
2)  [Optional]  Back up the Downloads folder which contains all the Nexus mod archives.  (_While this is not required to play UltSky, it will come in handy in case you need to re-install the mod pack using Wabbajack. Just point the Wabbajack installer to this folder as the "Download location" and it should detect all available mods, in which case it will only download the ones that need to be updated from Nexus.  This will reduce the installation time considerably._)
3)  [Recommended]  Backup the ENB binaries and configuration files from the Skyrim game folder (the folder with TESV.exe)
     *  **d3d9.dll** 
     *  **enbhost.exe** 
     *  **enblocal.ini**
     *  **enbseries.ini**
     *  **enbseries folder**
     
Note: I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143/?tab=description) or a similar tool for this.  The app can backup and store multiple ENB configuration profiles, and restore them with a few mouse clicks.

# Restoring UltSky from a backup:
1)  Start with a fresh installation of Skyrim Legendary Edition from Steam, or from a Steam backup.
2)  Refer to the [Wabbajack install guide](https://docs.google.com/document/d/1JxbNnYpLp2seYQxfFfyUKWkXoVDpjGgUdk_HjA8-kDE/edit) and install any additional requirements such as the latest **64-bit Java** and **.NET framework**.
3)  Copy the main UltSky folder (the one with ModOrganizer.exe) from your backup to a location of  your choice, preferably on your OS drive.   Use a short path, close to the root directory, e.g. **C:\US** .
4)  Start **ModOrganizer.exe** from the Ult Sky folder, go into **Settings > Paths**, and update the paths for **Base Directory** and **Downloads**.  Base Directory is the path to ModOrganizer.exe, and Downloads should point to the folder with all the Nexus mod archives.  The rest of the paths (Mods, Caches, Profiles, Overwrite) should already be correct and should begin with **%BASE_DIR%**/
5)  Complete the Post-installation steps from the Wabbajack guide.

If you wish to restore your ENB configuration from a backup, copy the above files to the game folder.
