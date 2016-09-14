# opentoonz-papagayo.hta
It's a very handy hta/javascript gui that inserts and converts a papagayo voice.dat in a copy of your existing toonzfile and saves it to a new opentoonz scenefile.

To use it, you must make mouthshapes for your character. 
The .hta file has a variable containing which frame numbers to use. 
Use or adjust these to suit your character. Use the same format as shown now ( 0001 - 0011 ).

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


# Converting the papagayo data 
1. Select your opentoonz (template) file
2. Select your papagayo exported voice(.dat) file
3. Select the level(s) you want to insert the keyframes in.
4. Convert and save to new scenefile
5. Open your exported.tnz in Opentoonz, and add the audio.wav you used in papagayo on the first frame. 

# Screenshot of the gui
<img src="screenshot.png">

>I'm using an updated version of papagayo that has much better language support. Get it here:
https://morevnaproject.org/papagayo/

# Some animation footage made using this converter: 

[Donald Trump is Learning to Lie...](https://youtu.be/4O1BLhU_a3Q "Trum Petty on youtube")
[Deat Satan, real tweets to the dark lord ](https://youtu.be/9i4RP6qqUTI "Dear Satan")
 





