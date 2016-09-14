# opentoonz-papagayo.hta
It's a very handy hta/javascript gui that inserts and converts a papagayo voice.dat in a copy of your existing toonzfile and saves it to a new opentoonz scenefile.

To use it, you must make mouthshapes for your character. 
The .hta file has a variable containing which frame numbers to use. 
Use or adjust these to suit your character. Use the same format as shown now ( 0001 - 0011 )
It uses preston blair format for now.

var mapObj = {
   rest:"0007",
   AI:"0001",
   E:"0002",
   O:"0003",
   U:"0004",
   etc:"0005",
   WQ:"0006",
   MBP:"0007",
   L:"0008",
   FV:"0009"
};


# Converting the papagayo stuff 
. 1> Select your opentoonz (template) file
. 2> Select your papagayo file
. 3> select the level(s) you want to insert the keyframes in. 
. 4> convert and save to new scenefile

<img src="screenshot.png">

I'm using an updated version of papagayo that has better language support. Get it here:
https://morevnaproject.org/papagayo/

# Some animation footage made using this converter: 

https://youtu.be/4O1BLhU_a3Q 

https://youtu.be/9i4RP6qqUTI



