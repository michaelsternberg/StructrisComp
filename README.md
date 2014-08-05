A slightly modified copy of Martin Haye's **Structris**, an elegant Tetris-esque game
for the Apple II written in Applesoft BASIC. This version was created to 
support a Structris tournament held at Kansasfest 2013. 

The differences are:

  * Simple score added (1 point per row cleared - no bonus opportunities).
  * Play can progress beyond level 10 - your blip becomes less visible with every 10-level wave completed.
  * Removed (R)estart option.
  * Used SLAMMER 1.1.1 - original SLAMMER may crash on unenhanced Apple IIe's

Martin's original version of Structris is available at
[https://bitbucket.org/martin.haye/structris/downloads](https://bitbucket.org/martin.haye/structris/downloads)

Note: For the purpose of the Kansasfest tournament, an additional command alongside (N)ew and (Q)uit was added to provide a shortcut to level 5. This was used during seeding to minimize the player's time commitment to set a score. The version shared here has that feature disabled. Otherwise, if a player starts at level 5 and completes level 10, the Tetris-esque well for level 11 is not drawn correctly and causes the program to end abnormally. I'd rather disable it than find out what the deal is. :)