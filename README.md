# opentoonz-papagayo.hta
Simple hta (hypertext application) that converts papagayo voices to xml to be pasted in your scene-file in opentoonz.
I suggest using a column for the mouth, but you could even customize the exact xml-layout in the hta.
Create a column with mouth in you scene and save the pli. You need 10 frames of mouthshapes, or 9 if you use the MBP shape as rest position.

You should now edit the configuration in the hta so it matches your character. Use a notepad to open the file, and adjust the framenumbers to the framenumbers in the .pli file of matching your characters mouth. Also change the level-id to your characters mouth then save and doubleclick the hta file to launch it.

Open the papagayo.dat voice file by browsing to it. It should convert to xml cell elements in the textfield to your configuration.

Copy the xml and open (a copy of) your scenefile (which has a .tnz extension) in a notepad or another texteditor. Search for "cells" and look for the one containing the level-id of the mouth.pli of your character.
The xml in the textbox should be pasted in the tnz file between the [cells] ... [/cells] containing the level-id of the mouth of your character.




