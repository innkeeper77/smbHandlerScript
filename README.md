# smbHandlerScript
WIP: Script to handle SMB mount/unmount on Ubuntu only on specific networks (preventing freezes)

This is currently a script designed for my personal use, but you may find it helpful. Features are missing, and it requires significant manual configuration!

This script allows me to mount and unmount my NAS SMB shares automatically, without using FSTAB, and only attempting to mount when I am connected to my home network. This has improved performance on my laptop for whenever I take it to a different network, and unmounts the shares if I drop off the network automatically, preventing the file browser from hanging. 

Tested on Kubuntu 19.10. The script depends on the built in ubuntu functionality to run a script on a network event. In order for this to work, a copy of the script is placed in the correct directory for each event, and is configured manually to run the appropriate commands on said event.


Documentation is currently inside the script itself

MISSING FEATURES: 
1. Handling for ethernet, right now it just handles a single wireless SSID.
2. Clean documentation

LICENSE:
MIT. Do whatever you want, use or reuse at your own risk.
