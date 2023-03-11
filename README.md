# FixYourEDrums
Apple Scripter Plugin script to correctly map EDrums in MainStage

Did you get an Alesis Nitro Mesh but hate that the Hi-Hat and Crash Choke don't work out of the box with MainStage or Logic Pro? This script for the Scripter Plugin that will fix both of those for you!

Thanks to everyone at logicprohelp.com who discussed how to handle cymbal choke in [this thread](https://www.logicprohelp.com/forums/topic/108702-drum-kit-designer-cymbal-chokes-amp-roland-v-drums/).

## How to add the script to your MainStage concert

1. Save the "alesis_nitro_mesh_fixes.pst" file from this page to your computer
1. Open your MainStage concert
1. Find the channel strip containing your Drum Kit Designer plugin (it should say "Drum Kit" in the Input section)
1. In that same channel strip, click on the "MIDI FX" section to choose a plugin and select "Scripter"
1. In the Scripter plugin window that pops up, click on the drop-down menu near the top that says "Factory Default" and select "Load..."
1. Find and open the "alesis_nitro_mesh_fixes.pst" file that you just downloaded

You're done! The hi-hat middle position and the cymbal choke should now be working
- You can change set how "open" you want the hi-hat middle position to be by adjusting the "Hi-Hat Adjust" slider
- Don't forget to save your concert with these changes or you'll have to add the Scripter plugin again next time!
