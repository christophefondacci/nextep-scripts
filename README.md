# Building neXtep binaries

## Install target platforms

You first need to install target RCP platforms as neXtep will build for Mac OS X, Windows and linux 32 and 64 bits.

The following instructions have been copied from https://wiki.eclipse.org/A_Brief_Overview_of_Building_at_Eclipse#Preferred_way_of_doing_multi-platform_builds:

The preferred way of getting the platform specific artifacts is to just add them to the target platform. There is no need to look-up and download the "DeltaPack" if you follow these instructions.

This is works not only with the Mars release, but also previous releases, as well.

* Open Window/Preferences.
* Find PDE/Target Platform
* Select your (active) target platform
* Click Edit
* Click Add
* Select "Software Site"
* Click Next
* In "Work With" type: http://download.eclipse.org/eclipse/updates/4.6 (replace 4.6 with your current version)
* Check "Eclipse RCP Target Components"
* Check "Equinox Target Components"
* Uncheck "Include required software"
* Check "Include all environments"
* Press Finish
* Press Finish
* Press OK
