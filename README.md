# KSA-Mods-Library
Literally just a library for different KSA mods and their links

## How to add your mod
Create a pull request containing the following
 - a file in the mods folder containing your title, description, and download link (see below for more details)
 - modify the mods.json file to have a path for the above file

## mods folder
to add the title of your mod, just add "Title": "{Title goes here}, same goes for Description_Short and Description_Long.

to add dependencies, add a dependencies block using "Dependencies": []
add the mod id (the one listed in the mods.json file) there or you can add Core or StarmapAPI for those things to be forced enabled.
dependency type 0 is recommendation, 1 is requirement, and 2 is unsupported

you can add your download and modpage by putting the links to them in the respective blocks

a full example can be seen at [the KSP-Redux JSON](https://github.com/PlazmaBoltz/KSA-Mods-Library/blob/main/mods/KSP-Redux.json)
