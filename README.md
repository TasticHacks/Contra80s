# Contra80s
![Contra80s - Logo](images/contra80s-wheel-alt1.png)
# Description
> Contra 80s is an HD graphics upgrade that reimagines Contra as an action-packed ’80s thrill ride!  Play as Dutch from Predator and Rambo as you battle through worlds inspired by iconic action, sci-fi, and horror films—including Predator, Aliens, The Terminator, The Thing, and The Empire Strikes Back.
> 
> With the 40th anniversary of both Aliens and Predator upon us, time feels right to unleash this hard-hitting 80s update to this NES classic.  So lock & load, and remember… if it bleeds, we can kill it!

## About the ROM Hack:
Mesen is a free Nintendo Entertainment System (NES) emulator.  Mesen HD Packs are fan-made mods that replace a game’s original 8-bit graphics with high-definition textures, custom sprites, and enhanced audio in real time.  

Contra 80s is a free Mesen HD Pack by developed by Tastic for the original Contra (1988) on the NES.  

This HD pack is 2x scale, so it plays at 512x480px default resolution in the Mesen emulator.  Players 1 & 2 sprites have been replaced by Dutch (Arnold) from Predator and Rambo.  All 8 stage levels and enemies have been replaced with new HD backgrounds, inspired by various 80s movies.  Title cards have been added before stages, tying together a new storyline that weaves in the 80’s movies into a single game narrative.

# Mesen HD Packs – Installing and Using
In general, you can install and use Mesen HD Packs by doing the following 3 steps:
1. Install the MESEN NES emulator
	  *	Download and install the Mesen NES emulator and use it to play the Contra ROM. Game file.
	  *	Downloads: https://www.mesen.ca/
2. Find Correct ROM Game file
	  *	be sure to find that correct game ROM file that matches the specified SHA1 hash and play it using the Mesen emulator.  This ROM is the original, unaltered Nintendo game.
	  *	Example: the correct ROM to use with Contra 80s to use has a filename Contra (U) [!].nes and matches the SHA1 hash: C9EA66BB7CB30AD5343F1721B1D4D3219859319B
	  *	Find where ever ROMs are found
3.	Place HD Pack Folder in Correct Location
	  *	unzip and place the HD Pack folder in the correct location being used by the Mesen emulator for HD Packs.
	  *	The folder name must match the ROM game file name exactly (minus the .nes extension).  So, for example:
    * ROM name:  Contra (U) [!].nes
    * Folder: C:\Users\bob\Documents\Mesen2\HdPacks\Contra (U) [!]\hires.txt
    * Also, make sure the “Enable HD packs” is checked in the Mesen emulator settings:
       * ![Mesen-EnableHDPacks1](images/Mesen-EnableHDPacks-1.png)
   
# RetroPie (Raspberry Pi) - Usage / Install:
* If you’re like me, and like doing your retro gaming on a Raspberry Pi (using RetroPie), then you can do this by:
	* place HD packs in folder:
		*	/home/pi/RetroPie/BIOS/HdPacks/
		* name the sub-directory with the HD pack for each game in a folder named directly after the ROM filename, example:
		*	ROM name:  Contra (U) [!].nes
		*	Folder: /home/pi/RetroPie/BIOS/HdPacks/Contra (U) [!]/hires.txt
	* Renaming - So if you want to rename the ROM to something like:
		*	New ROM name:  Contra80s.nes
		*	New HD pack folder path:  /home/pi/RetroPie/BIOS/HdPacks/Contra80s/hires.txt
	* Run the game in Mesen emulator:
		*	lr-mesen
      * ![RaspPi-lr-mesen-1](images/RaspPi-lr-mesen-1.png)
		*	package can be installed for RetroPie-Extra:
			*	https://github.com/Exarkuniv/RetroPie-Extra
	* enable loading of HD Packs within the RetroArch menu while running the game
		*	Press Select+X(North) to while playing to enter RetroArch menu
			*	Go to Core Options -> Video -> Enable HD Packs = On
        * ![RaspPi-lr-mesen-enableHDPacks-1](images/RaspPi-lr-mesen-enableHDPacks-1.png)
