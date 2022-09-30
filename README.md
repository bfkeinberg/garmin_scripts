# garmin_scripts
A collection of AppleScripts to automatically back up activities, move route files onto the device, or update a map from Wandrer.com

This is a set of scripts I've developed over time to make it easy to do the routine tasks that I used to manually do dragging and dropping files.

When I plug in my device, it automatically moves any activity files into the folder that I use for that purpose on Dropbox, and if it finds a map that I've downloaded from Wandrer.com it puts that on my Garmin device, replacing any that is there.

Likewise if the device is already mounted if I download any courses as fit files (e.g. from RideWithGps.com or from Strava) they will be moved into the New Files folder on my Garmin.

## Contents 

- ```autoCopyActivity.scpt``` Runs when you plug in your garmin and installs Wandrer maps. 
- ```Copy Garmin activities.scpt``` Copies activities from your garmin into a designated folder in your home directory.   RUns when you plug in the Garmin.
- ```Route to Garmin.scpt``` Monitors the Downloads directory and copies any .fit files from your download directory to the garmin.  

## How to install the scripts.

- Download the scripts from github


Details here: https://developer.apple.com/library/archive/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide/WatchFolders.html 
- 