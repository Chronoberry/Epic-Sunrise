Plugin Installation
===================

Installing third-party addons
=============================
Third party developers can extend Construct 2 with new plugins, behaviors and effects (collectively referred to as "addons") using the Javascript SDK. Many addons can be found in the Plugins for Construct 2 forum.

Only install addons from developers you trust. Malicious addons have the potential to compromise the security of your project, or have hidden unwanted features like surprise adverts or tracking users. Badly written addons can also cause bugs or glitches in your game. While addons can be useful, remain vigilant about them, especially in regards to whether the developer seems trustworthy and if they regularly maintain their addon to fix problems that arise.

If you have problems with third-party addons, you must report the issues to the developer who provided them. Scirra cannot offer any support for third party addons whatsoever.

Installing new addons (.c2addon files)
======================================
Recently developed addons are installed from a file with the extension .c2addon. Simply download the .c2addon file, then drag and drop the file in to the Construct 2 window. Construct 2 will prompt to ask if you want to install the addon. If you approve the install, you must restart Construct 2 before the addon becomes available.

You can also drag-and-drop multiple .c2addon files in to the Construct 2 window and you'll be prompted to install each of them in order.

Installing older addons
=======================
Some addons were developed before Construct 2 supported .c2addon files. These are typically distributed as a collection of files in a zip file. To install them, close Construct 2 and copy the files to the appropriate place:

<install path>\exporters\html5\plugins for plugins
<install path>\exporters\html5\behaviors for behaviors
<install path>\effects for effects

Note that each plugin and behavior has its own subfolder in the above directories; make sure you copy the addon files to their own subfolder like the others in that directory. Effects however are simply a .fx and .xml file that all go in the same folder.

Restart Construct 2 and the addons should then appear in the editor.

Addon management
================
When installing .c2addon files, Construct 2 will attempt to copy the addons to two places: both the install directory, and the AppData folder for the current user (%appdata%\Construct2). This means even if you don't have permission to write files to the install directory you can still install addons.

If you use Construct 2 portably, addons may disappear if they only exist in the AppData folder on the local computer. To take your addons with you, either take a folder with all your .c2addon files with you, or make sure Construct 2 has permission to write to its install directory when installing the .c2addon files by running it with Administrator privileges.