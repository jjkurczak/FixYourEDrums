# FixYourEDrums
Apple Scripter Plugin script to correctly map EDrums in MainStage

Do you have an Alesis Nitro Mesh but wish the Hi-Hat and Crash Choke would work out of the box with MainStage or Logic Pro? This script for the Scripter Plugin will fix both of those for you!

Thanks to everyone at logicprohelp.com who discussed how to handle cymbal choke in [this thread](https://www.logicprohelp.com/forums/topic/108702-drum-kit-designer-cymbal-chokes-amp-roland-v-drums/).

## How to add the script to your MainStage concert

1. Download [alesis_nitro_mesh_fixes.pst](https://github.com/jjkurczak/FixYourEDrums/releases/download/v0.2/alesis_nitro_mesh_fixes.pst) to your computer
1. Open your MainStage concert
1. Find the channel strip containing your Drum Kit Designer plugin (it should say "Drum Kit" in the Input slot)
1. In that same channel strip, click an empty spot in the "MIDI FX" slot to add a midi plugin and select "Scripter"
1. Plugins with settings, like Scripter, can save and load those settings to .pst files, which is how you'll load the fixes here
1. In the Scripter plugin window that pops up, click on the settings menu near the top of the window that says "Factory Default" and select "Load..." to pick the new Scripter settings
1. Find and open the "alesis_nitro_mesh_fixes.pst" file that you just downloaded

You're done! The hi-hat middle position and the cymbal choke should now be working
- You can set how "open" the hi-hat middle position will sound by changing the "Hi-Hat Adjust" slider
- Don't forget to save your concert with these changes or you'll have to add the Scripter plugin again next time!
