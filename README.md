![HIDE](https://user-images.githubusercontent.com/46191274/124802325-d8433800-df25-11eb-85ce-46bf37e12300.png)

# HIDE
IDE for the HLA programming language

This is a HIDE project file, use HIDE to compile.
You can download HIDE from https://sites.google.com/view/androth/home/high-level-assembly

The project is setup to look for a HIDE_WORK folder in the same tree level as the HIDE folder as a build target. This build target folder should be a copy of a standard HIDE folder.


# CHANGE LOG
## v1.7.10
	- consolidated the keywords .ini files into smaller number of groups.
	- Data folder now contains HLA_Keywords.ini, x86.ini, resources.ini, custom.ini
	- Added 2 new groups, odin.ini and go.ini those groups will be loaded if HIDE opens
	  .odin or .go files respectively.
	  all the other group files have been removed.
	  
## v1.6.64
	- Added menu option F10 to launch kmake on "Build.kmk" in project root folder

## v1.6.63
	- start of cleanup code with the possible intention of making HIDE
	  more language agnostic.
	- removed NOTES from output, removed unused 'anchor' button from side windows
	- loading and saving the resource images in a modern image editor fixed the pale
	  images in the Properties Panel buttons.
	- removed the now unused captionbutton.hla unit
	- fixed PATH envrionment getting messed up if there is a USER defined path and "Set" is clicked in project manager

## v1.6.3
	- Fixed Insert File at Cursor crash
	
