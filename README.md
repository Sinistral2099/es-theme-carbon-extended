# es-theme-carbon-extended

Theme 'carbon' v2.4 - 08-16-2016 by Rookervik
based on simple(c) Nils Bonenberger - nilsbyte@nilsbyte.de - http://blog.nilsbyte.de/
For use with EmulationStation (http://www.emulationstation.org/)


Fonts:
Users can use any font they would like with the theme. Just copy your font to /etc/emulationstation/themes/carbon/art folder. Rename the original font "Cabin-Bold.ttf" to "Cabin-Bold.ttf.backup" and then rename your font to "Cabin-Bold.ttf". This will have the theme use your font instead of what comes with Carbon.

Gamelist Font Size:
To change the font size of the Gamelist, open the "carbon.xml" with a text editor, look for the tag <gamelist> and find a tag inside called <fontSize>. The original value is 0.03. A small change makes a big difference in size. If you want smaller gamelist names, try 0.02. If you want larger, try 0.04. You can even go further by trying 0.015.

Colors:
To change the colors open carbon.xml with a text editor. Choose a color and find it's hexidecimal value. Some examples are found in the carbon.xml file. Find all occurances of "8b0000" and replace them with your chosen color. Such as Orange: ef710b. Save the carbon.xml and exit. To change the color to another color after the first change, search for your old color, and replace it with a new one.

Sounds:
To change the sound effect, replace /art/scroll.wav with what ever WAV file you would like. Carbon theme will play what ever is called "scroll.wav" in the /art folder.

Changelog
=========

===08/16/2016===
Added Super Grafx
Added PC Engine CD-Rom�
Added Turbo Grafx CD
Removed metadata labels (only the actual meta data is shown)
Re-positioned elements slightly

===07/08/2016===
Complete re-write.
Simplified all system theme.xml files.
Theme color can be changed by finding and replacing colors in carbon.xml
UI flipped for left-to-right reading order
Meta-data tags reduced to: released, genre, players, and description
Kid-Friendly icons and code added
Flipper sound removed

===9/19/2015===
Missing controllers added:
Colecovision
Gamecube
PS2
X-11
Wii

