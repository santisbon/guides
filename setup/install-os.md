# Do a clean install of the OS

On macOS download the new version from System Preferences, Software Update and create the bootable media with:
```Shell
sudo /Applications/Install\ macOS\ Monterey.app/Contents/Resources/createinstallmedia --volume /Volumes/Untitled
```
where Untitled is the name of the external drive you are using.  

If you have an Intel-powered Mac here's how to install macOS from a bootable installer:
1. Plug in your bootable media.
2. Turn off your Mac.
3. Press and hold Option/Alt while the Mac starts up - keep pressing the key until you see a screen showing the bootable volume.

If you have an Apple silicon Mac here's how to install macOS from a bootable installer:
1. Plug in your bootable media.
2. Turn off your Mac.
3. Press the power button to turn on the Mac - but keep it pressed until you see the startup options window including your bootable volume.  

Open Finder and show hidden files with Command + Shift + . (period) or with
```Shell
defaults write com.apple.finder AppleShowAllFiles TRUE; killall Finder
```