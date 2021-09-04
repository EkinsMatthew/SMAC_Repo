SID MEIER'S ALPHA CENTAURI
README.TXT 1.0I
1/4/98

SINGLE PLAYER

IMPROVING PERFORMANCE

If you are experiencing performance problems, try some of the following tips:

*  Included in the Alternative Art folder on the CD-ROM is a Low Res Caviar folder. Copy the contents of this folder to the directory you installed the game to. The default is c:\program files\firaxis games\sid meier's alpha centauri. These files reduce the detail in the units, but can improve performance.
*  Reduce your resolution to 800 x 600, rather than 1024 x 768. This can greatly improve all game performance.
*  Disable the sound using the Audio/Visual Preferences menu.
*  Disable map animations, sliding windows, and sliding scrollbars.
*  Enable the following preferences: Move Friendly Pieces Quickly, Fast Battle Resolution, Move Units with orders quickly, Don't Center On Units With Orders
*  Increase the amount of free hard drive space on the C: drive.
*  Increase the amount of RAM in your system.
 11:55 AM 1/7/99
NEW FEATURES

* Right click on a Pact Brother from commlink menu to end a pact.

LAPTOP INSTALL

This install size copies the very minimum files to the hard that are required by the game to operate. It also alters the default game preferences to improve over performance.

COMPLETE INSTALL

This install copies the entire contents of the CD-Rom to the hard drive. It requires 360 megabytes of hard drive space.

GAMMA CORRECTION

We've added a Gamma Correction feature to allow the customer to adjust the brightness of the palette without adjusting their monitor. It is accessible from any of the preference menus. The default value is 1.0.

WINDOWS NT

Almost all features of SMAC should work under Windows NT 4.0. You'll need to obtain NT Service Pack 3 or higher from Microsoft and install it, which includes DirectX 3 or higher support. Note: Sound support under NT currently requires us to use emulated drivers; this can in some cases produce poor sound results, including static and sound breaking up.

CPU OVERCLOCKING

If you experience random crashes and you are overclocking your CPU (especially with AMD K-5 and K-6 processors), try returning your CPU speed to it's original setting. 

MOVIE PERFORMANCE

If your computer has problems playing some of the in-game movies, verify that you are not using any 16-bit real mode drivers for the CD-ROM drive. You can check this by opening the Control Panel and choosing the System settings. Under the Performance tab, there is a line for File System. This should read 32-bit. If it has anything else in that line, contact the manufacturer of your CD-ROM drive for updated Windows 95/98 drivers. If you still experience problems playing movies, try adding 'DirectDraw=0' to the Alpha Centauri.ini file in the install directory.

ADDITIONAL TWEAKS

Once the game is installed, a file is created called "Alpha Centauri.ini". This file contains various settings and preferences for the game, but can also be edited by the user. The following commands will allow you some control over the look of various parts of the game.

WindowsFileBox=1
Settings this to 1 allows you to use the traditional Win95/98 file navigation dialog.

MainFontSize=16
You can increase or decrease the size of the font used throughout the game. 

DirectDraw=0
Settings this to 0 disables DirectDraw. This disables the automatic window resolution resizing during program launch.

Video Mode=800 or Video Mode=1024
This forces the screen resolution to either of these two sizes.

8BitMovieSound=1
This forces the sound quality to 8-bit from the original 16-bit. If your sound card has DirectX compatibility issues, this may improve movie performance.

TROUBLESHOOTING - If your computer has problems playing the game (crashes, returning to desktop, etc.), please try the following:

1. Reinstall DirectX 6. Run the DXSetup.exe program that is available on the CD-ROM in the \DirectX folder.

2. Rename the SOUND.DLL to SOUND.DL_. While disabling the sound, it may correct your original problem.

3. If you receive the message "CPU Not Supported", and you have a non-Intel processor such as an AMD K-5, try to run the game anyway. Many AMD processors show up as a 486 in verification tests, but if your machine is 'Pentium Compatible', it shouldn't be a problem.

4. Increase amount of free hard drive space on the C: drive, especially if you have 16 or 32 megs of memory. 

5. Let Windows handle your swap file size. This can be adjusted by running the System Control Panel, selecting the Performance menu tab, then the Virtual Memory button, and selecting "Let Windows manage my virtual memory settings".

6. Update the Windows 95/98 drivers for your Video card, Sound card, and Monitor.

MULTIPLAYER

New Features:

* Change symbol next to faction name in 'commlink' menu to 'null' (zero with a slash through it) by clicking on it to ignore all messages from a player. 

NON-SIMULTANEOUS MULTIPLAYER:

A feature we added is non-simultaneous movement in multiplayer games. Benefits of this mode include significantly less packet transmission (to improve performance), the ability to execute diplomacy without your turn clock running out, and the luxury to fine tune your bases while other players complete their moves.  Disable the Simultaneous Move option on the Multiplayer Setup screen to use this feature.  The game plays essentially the same as the simultaneous move game, except when other players are making their moves, you maintain control. Except for actually moving units, you can access any base, any report screen, initiate or participate in diplomacy, and many other actions.

ALPHAHQ.NET:

To facilitate internet (TCP/IP) games, we have provided a web-based match making service called AlphaHQ.net. Point your web browser to www.alphahq.net to join. Once there follow the on screen directions to begin playing as quickly as possible.
** MAKE SURE YOU DO NOT HAVE ALPHA CENTAURI RUNNING BEFORE JOINING ALPHAHQ.NET GAMES. ** 

VOICE OVER DATA TROUBLESHOOTING:

One of the features of Alpha Centauri is the ability to use a microphone connected to your sound card for real-time voice communication during multiplay games. Below are some troubleshooting techniques you may try if you're experiencing difficulty using this feature.

VOICE LINK TIPS:

1. Before attempting to use the voice link feature in Alpha Centauri we recommend testing the recording functionality of your sound card with the Sound Recorder the comes with Win '98 / '95.  If you can get that working then the voice link will most likely work.

2. Keep in mind this feature is designed to work using as little bandwidth as possible so quality will be marginal. However you should be able to understand the person who is talking. If not, try experimenting with microphone volume , mic placement, and speech volume. It may not be pretty but it sure beats typing messages.

3. If you're unfamiliar with the Windows record settings here is how to access them: First open up the "advanced mixer" by double clicking on the volume control icon located on the Windows task bar (looks like a speaker). If this icon is not present you need to enable it by opening the control panel, multimedia properties and checking the "show volume control on taskbar" checkbox. By having the volume control on the taskbar you can adjust the settings while you in the game.
Once the "advanced volume control" is showing - it looks like a mixer with a number of sliders - look for a microphone slider. If you don't see it pull down the options menu, look for a microphone check box and check it and hit ok. This will add a microphone slider to you playback volume control. Make sure that slider is muted, this will prevent feedback. Now pull down the options menu and select recording and hit OK. From there you can adjust your volume. Once again if you don't see the microphone slider for the record volume control pull down the options and check the microphone check box.
 
4. Many sound cards come with a mic boost feature. While in the record mixer pull down the menu and select "Advanced." Look at the mic slider.  If there's an "Advanced" button, hit it and look for a mic boost check box.  Experiment with it to get the best sound.

5. Use the voice link like a walkie-talkie. Press down and hold the '\' key, talk and when finished let it up.  Only talk in turns because the system is half-duplex (It can't transmit and receive at the same time).  Avoid using it during the upkeep phase in multiplayer since during that time it's possible to let up on the key and not stop the recording. You know it's working when the games sounds stop. If the games sounds don't return after letting up (during upkeep) then wait till upkeep is finished and press and let up on the key again - the sound should return.

KNOWN PROBLEMS:

1. During the upkeep phase in multiplayer recording may get stuck causing game sounds to stop. just press the '\' key till the sound returns.

2. General poor sound quality of voice over data.

3. We decided to leave game sounds on during voice link reception and incoming messages can sometimes get garbled with voice stuff in the game.

TROUBLESHOOTING:

1. Some users may experience problems when playing Alpha Centauri using America Online (AOL) as their connection to the internet. Please consult the web page (www.firaxis.com) for updated information concerning this issue.

2. Modem TCP/IP games with more than 2 players may degrade game performance on some networks.  We will keep updated information on TCP/IP game performance on our web page.

SCENARIOS:

There are a number of pre-generated scenarios provided with the game in the '\scenarios' directory.
 
*The first three, labeled "1Explore", "2Build", and "3Conquer", are tutorials designed to get beginners up and running with the game. *The "Faction v Faction" folder contains three scenarios pitting a faction against its archenemy; these may be played as single-player or multiplayer scenarios.
 
*The three folders beginning with "MP..." are designed as balanced multiplayer scenarios with defined goals and short time limits. Try them out for a shorter, sharp, fun multiplayer experience!

*The last scenario, "SP--7 PlayerA" puts the factions arrayed around a central continent in a struggle for territory.

Enjoy,

The Firaxis Games Team
