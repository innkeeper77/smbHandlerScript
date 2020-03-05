# smbHandlerScript
WIP: Script to handle SMB mount/unmount on Ubuntu only on specific networks (preventing freezes)

This is currently a script designed for my personal use, but you may find it helpful. It allows me to mount and unmount my NAS SMB shares automatically, without using FSTAB, and only attempting to mount when I am connected to my home network. This has improved performance on my laptop for whenever I take it to a different network, and unmounts the shares if I drop off the network automatically, preventing the file browser from hanging.

Tested on Kubuntu 19.10

Documentation is currently inside the script itself

MISSING FEATURES: 
Handling for ethernet, right now it just handles a single wireless SSID.
