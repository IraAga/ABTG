## ABTG - Automated Bluetooth Traffic Generator

    OS: Arch Linux
    Dependencies: tshark, xdotool, awk, ffmpeg, skyperforlinux, discord, spotify, chromium, thunar

### Description: 


	Opens the given app, which creates bluetooth traffic. The bluetooth 
	device should be already connected with the host before this script
	starts running. The screen is captured by the script for debug purposes.
	The generated traffic gets captured using tshark. The duration of the
	capture is determined by the user of the script.

### Usage:
    bash reccap.sh <app_name> <duration>

        $app_name = discord/skype/youtube/spotify/music 
        $duration > 60
    
Given the 'app_name' that use to generate some king of audio output 
And 'duration' value representng the overall length of the procedure

###### (!) NOTE (!)
IF you want to use this script you must first fix the coordinates that xdotool 
uses on your specific system. The default values are used on a Lenovo L13 ThinkPad
with 13.3 inch display, running Arch Linux.

