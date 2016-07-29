# opentoonz-papagayo.hta
Simple hta (hypertext application) that converts papagayo voices to xml to be pasted in your scene-file in opentoonz.
I suggest using a column for the mouth, but you could even customize the exact xml-layout in the hta.
Create a column with mouth in you scene and save the pli. You need 10 frames of mouthshapes, or 9 if you use the MBP shape as rest position.

You should now edit the configuration in the hta so it matches your character. Use a notepad to open the file, and adjust the framenumbers of variable mapObj to the framenumbers in the .pli file that contains your characters mouth. Also change the level-id to the level-id of your characters mouth. You should open a scene file (.tnz) to find out what level-id it has. Just search for ".pli".
If you're done adjusting, save and doubleclick the hta file to launch it.

Open the papagayo.dat voice file by browsing to it. It should convert to xml cell elements in the textfield to your configuration.

Copy the xml and open (a copy of) your scenefile (which has a .tnz extension) in a notepad or another texteditor. Search for "cells" and look for the one containing the level-id of the mouth.pli of your character.
The xml in the textbox should be pasted in the tnz file between the [cells] ... [/cells] containing the level-id of the mouth of your character.

The version I'm using of papagayo is updated for more languages. Get it here:
https://morevnaproject.org/papagayo/



