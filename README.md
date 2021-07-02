# ABTG - Automated Bluetooth Traffic Generator

os: Arch Linux
required programs: tshark, xdotool, awk, ffmpeg

		apps: skyperforlinux, discord, spotify, chromium, thunar

Description: 
	- Given the 'app_name' we sample from 
	- And 'duration' value representng the overall capture time

	Opens the given app, which creates bluetooth traffic. The bluetooth 
	device should be already connected with the host before this script
	starts running. The screen is captured by the script for debug purposes.
	The generated traffic gets captured using tshark. The duration of the
	capture is determined by the user of the script.

(!) NOTE 
IF you want to use this script you must first fix the coordinates that xdotool 
uses on your specific system. The default values are used on a Lenovo L13 ThinkPad
with 13.3 inch display, running Arch Linux.
