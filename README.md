# Desktop-Claude-Linux-Mint
This is a build that creates a desktop AppImage of Claude, equivalent to the desktop apps for Windows and MacOS. You'll no longer need to load Claude in a browser.

Download the claude-electron-build.zip. Use the following commands from a terminal:

```bash
unzip claude-electron-build.zip
cd claude-electron-build
chmod +x build.sh
./build.sh
```

If your system is missing anything the script will report it and return the command to download what's missing. The final result will be an AppImage that will run natively in Linux Mint...I have not tried it on other distros.
