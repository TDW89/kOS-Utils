#kOS Utils

**This boot script is designed to offer some useful utilities to otherwise normal gameplay via the powers of the [Kerbal Operating System mod](http://forum.kerbalspaceprogram.com/threads/68089). Using it requires absolutely no coding skills whatsoever, however the script itself is well-commented and designed to be an example of how you can use kOS to automate various tasks in Kerbal Space Program.**

##How to install

1. Download and install kOS ([CKAN](http://forum.kerbalspaceprogram.com/threads/100067) is great for this!)
2. Download the kOS Utilities Script and place it in your [KSP install location]/Ships/Script folder (kOS will create this folder, however if you haven't run KSP with kOS installed, you may create it yourself).
3. Attach a kOS CPU to your craft of choice
4. In the tweakable menu for the CPU, select *boot_kos_utils* as the boot script
5. Launch your ship and follow the instructions!

##Utilities included

* Panel Util - Opens and closes your ship's solar panels based on whether you're in atmosphere or not. This prevents you from forgetting to open them and running out of power, or forgetting to close them and breaking them off in flight.
* Gear Util - Raises and lowers your ship's landing gear and/or landing legs based on how high you are off the ground. 100m is the default setting, although that can be changed in the script if you so desire.
* Chute Util - Automatically deploys your ship's parachutes if you're descending below 10km and the chutes show as 'Safe To Deploy' in the right-click menu. Best used for capsules returning from orbit.
* RT Antenna Util - Automatically deploys any extendable RemoteTech antennas once you leave the atmosphere and retracts them when you re-enter. This prevents you from forgetting to open your antennas and losing contact with your probe. Will continue to function even if there's no RT connection!

I also left room in the menu for three more utilities for you to write! You can use the current utilities as an example of how to write one. Be sure to consult the [kOS documentation](http://ksp-kos.github.io/KOS_DOC/) and feel free to ask questions in the [/r/kOS](https://www.reddit.com/r/Kos) subreddit.

If you write a utility that you feel should be included with this release, I'll happily entertain a pull request!