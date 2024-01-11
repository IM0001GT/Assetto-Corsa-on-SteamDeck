# Assetto-Corsa-on-SteamDeck
Assetto Corsa on the steamdeck is working once again, as you've probably noticed none of the online guides are working (again), so here is one that works.

This is tested with an up to date SteamOS, and no major modifications


Assetto Corsa on the Steamdeck

Working as of Wednesday, Janurary 10th, up to date LCD and OLED Deck

1. Set your deck to writable (lots of guides online, it involves setting a password for your deck)

2. Install Proton 5.0 by searching it at the top of your game launcher. You won't be Using it, but it's needed to allow the PreRequisites to install and not hang. (primarily DirectX)

3. Install Assetto Corsa normally via Game Launcher 

4. Go into desktop mode and run the game, to setup the file structure, the game will crash, let it do so naturally, the setup process will take around 30 minutes from here till the game works

5. We are going to delete our current compatibility settings, go to Home/deck/.local/share/steam/steamapps/compatdata/244210/pfx, and delete the pfx file

6. Install protonup-QT, and then install proton-GE 7.20, within protonup-QT you will have the option to make AC run with it

7. Go to steam and set AC to force compatibility and run with 7.2, let the game start, it will chug along for 10 minutes or so, as it is installing dependancies, it will crash naturally

8. This step is NOT MANDATORY, and only if you are curious about what is going on, set a tail to the winecfg file to see what dependancies are being installed. 

9. Once the game has crashed, run it again, this time it will run for 10 minutes and then the game will open, OR the game might crash again, do not panic, simply let the game run till it crashes then try again

10. Go ahead and close the game, and run the game for a third (or final) time, this time the game will install the final batch of dependancies and be ready to play

11. At this point I usually switch the forced Proton version to Proton Experimental since the game only needs the previous versions of Proton for Installing Prerequisites and not to actually run

12. Turn on 32-bit in the settings, otherwise the game will not work, additionally, as things are now the game does not work with game launcher mode, you will have to play it via desktop mode but don't worry, they are functionally the same, just go to settings and set your controls to controller instead of 
keyboard

13. Mods work and can be installed normally, however as things are now, Content Manager is not working, and I am looking for a way to get it up and running

14. Enjoy the best racing sim on the market, once again playable on Deck
