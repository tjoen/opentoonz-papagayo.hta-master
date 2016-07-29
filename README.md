# opentoonz-papagayo.hta
Simple hta (hypertext application) that converts papagayo voices to xml to be pasted in your scene-file in opentoonz.
Place the mouth on your character. I use a column for the mouth, but you could even customize the layout in the hta.
Copy the xml and open (a copy of) your scenefile in a notepad or editor. Search for "cells" and find the one containing the level-id of the mouth.pli of your character.
The xml in the textbox should be pasted in the tnz file between the <cells> ... </cells> contining the level-id of the mouth of your character.

You should edit the configuration in the hta so it matches your character.


