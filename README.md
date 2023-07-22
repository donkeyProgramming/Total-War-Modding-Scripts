# Total-War-Modding-Scripts
A collection of python scripts I write for my Total War Modding.

Some of these will be contained in a .blend file, opened in Blender.


## Prefab bmd file to Terry layer file.py

Only tested with Warhammer 3 .bmd,
Input a prefad bmd, it will output an xml file that you can open in Terry


## global_props bin file to Terry layers.py

Only tested with Warhammer 3.
Input a campaign's global_props.bin, it will output a bunch of xml Terry layers, one for each region in the campaign map
Put the xml layers in your Terry project's folder, and then copy+paste the stuff in terry_file_update.txt into your project's .terry file.
This might be missing a few things, but whatever is missing is very hard to notice when in-game.


## global props bin.bt

A template for use in 010 editor, a hex editor.


## prefab_bmd.bt

A template for use in 010 editor, a hex editor.


## S2TW_animation_import_export.blend 

For Shogun 2 Total War
Reads/displays animations, does not read/display models!
