# Save as PDF.scpt
## by Chris Sauvé of [pxldot](http://pxldot.com)


## Description
This script will automatically save the selected Word and/or PowerPoint files in Finder (or Path Finder, if you use it instead) as PDF files in the same directory. When first run, the script will prompt you to select either Word, PowerPoint, or both to save as PDFs, and will also ask you whether you would like to automatically delete the files that are converted using this script (can be changed by editing the `deleteConverted` property).


## Installation
Download the most recent version of the script. Once you have downloaded the script, navigate to your Application script folder located at `~/Library/Scripts/Applications/Finder`. Apple hides the Library folder in Mac OS X 10.7 or later by default, so the easiest way to get to this folder is to select the menu item `Go > Go To Folder...` in Finder.app. You may have to manually create an Finder folder in the `~/Library/Scripts/Applications` directory if you do not have any previous scripts for Finder (you may have to create more of the folders in the directory; if you don't have an Applications folder or even a Scripts folder, you will have to create those as well). If you use Path Finder, you can replace all of the above instances of `Finder` with `Path Finder` to install it for use with that application.


## Using The Script
There are countless ways you can run the script. If you are a pro user, you likely know even more ways than I do: options like launching the script from FastScripts, Alfred, LaunchBar, or a Keyboard Maestro macro are all available to you.

Your other option is to run the script from Apple's AppleScript menu. If you don't have a little script icon near the clock in your Mac's menubar, you need to turn this on manually. Open AppleScript Editor.app from your `Applications > Utilities` folder. Go to AppleScript's preferences by selecting `AppleScript Editor > Preferences...` from the menubar. On the "General" pane, you should check the checkbox to "Show Script menu in menu bar". Now, when in Mail.app, select the new script menubar item and you will see the script at the bottom of the list, ready to be clicked and run.


## Version History
- **0.2.0** (January 7, 2013): Added the choice to automatically delete converted files.

- **0.1.0** (December 29, 2012): Initial release.


## License
Use it, change it, repackage it, whatever. Try not to take credit for my work.