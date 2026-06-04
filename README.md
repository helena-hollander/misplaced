# misplaced
Repository for my BA project, containing a prototype of a TouchDesigner plugin for audioreactive visuals and projection mapping, using KantanMapper plugin. 

Welcome to this little corner of the internet! This is the official documentation and guide to MISPLACED, a audioreactive plugin for TouchDesigner. (2026)
Created to help build creative communities around live music events, by shaping any location into a space where we can explore and share good memories. 

MISPLACED is dedicated to people who crave community and want to practice safe spaces that value respect and intention. We hope this tool can inspire some presence in the everday hustle, and use technology to bring us physically closer, rather than seperating us. 
As an Open Source project, we want you to explore and mess around as much as you like, to truly build this tool as a community.


GETTING STARTED:
Before you can open the MISPLACED plugin, please install TouchDesigner's software from derivative.ca, and create a free account for non-commercial uses only. (Make sure you download the correct package for your device, and that you get the latest update.)
MISPLACED uses the plugin KantanMapper, natively included i TD, so remember to enable this in the settings as well. 

When you download your misplaced.zip folder, you will find an empty .tox file and a folder with a prepared project, ready to go. Choose whichever you want, depending on wether you plan on adding your own graphics, or play with MISPLACED own visuals. If your want to follow the tutorial further down, please choose the pre existing project. 

When you first open the prepared projectfile, dobble-click the project1 container, to enter. Your will see three containers: The Audiovisual Graphics, the MISPLACED Interface and the connected KantanMapper window. 
In the Audiovisual param, start by chosing your audio input device. (This could be your built in mic, a local audiofile or an external audio input device.) When you see colors appear in the window, the input works. (Should you not see anything, please go to next step, and turn up the GAIN slider, to increase the amount of audio input.)
Next, right click the middle container and click 'View' to reveal the MISPLACED VJ interface. Here you can play around with different slider parameters, to change the character of the visuals, which you can see updating live in the Preview window to the left.

**SLIDERS:**

GAIN: Turns the amount of audio input to the visuals up og down. (Does not change the volume, just the reactivity.)

RGB DELAY: Adds a delay on the RGB values, when the visual move. Like a rainbowy shadow. (Can be increased, by turning uo the SPEED and BRIGHTNESS alongside it.)

DISPLACEMENT: Creates a warped effect, making the circular shapes more distorted when increased.

BRIGHTNESS: Turns up the bottom effect, creating little shadows or roots beneath the top layer. Gives an illussion of depth and movement and lights up the overall top. 

PERIOD: The size of the noisefilters period. This can either create tiny, curly shapes or bigger, rounders shapes. 

HARMONICS: Sharpens the PERIOD even further, and makes the sketch even more scattered, when turned up. 

SPEED: Decides the speed of the animation and movement of lit up areas. 

