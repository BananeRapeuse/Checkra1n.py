<img src="litera1n.png" alt="logo">

# litera1n

An iOS/iPadOS Jailbreak for all A5-A11 devices based on checkm8 exploit
 
For libusb errors, refer to this guide: ["Click here"](https://www.smallcab.net/download/programme/xm-07/how-to-install-libusb-driver.pdf)

We are always in developement but you can also jailbreak (jailbreak is ready to use)

# Testers
<a href= https://github.com/BananeRapeuse/litera1n/blob/main/testers.md>Testers,</a>
DM me on discord: `frelon111` or reddit: `Ph0qu3_111` to be a tester,
all the testers will be added in the `"thanks to"` part of the [official website](https://bananerapseuse.github.io/litera1n) and on the [credits part of the github](https://github.com/BananeRapeuse/litera1n?tab=readme-ov-file#credits).

# RUN ALL OF THIS USING ADMIN COMMAND PROMPT

# Preinstall
git from https://git-scm.com/

python from https://python.org
### IMPORTANT
cd to the libusb folder after cloning/downloading and copy **libusb.dll** to c:/windows/system32 and c:/windows/syswow64 (only if 64bit) then run **infinstaller.exe** from libusb folder and install the .inf file by right clicking. AFter that copy **Libusb0.sys** to c:/windows/system32/Drivers and c:/windows/syswow64 (only if 64bit)

# Must do
- With iPhone 8/8+/X or in iOS 16+, you **must** disable passcode before jailbreak ! (Settings: TouchID/FaceID and code ----> disable the code)

- after cloning, cd into the folder and type `python main.py`
type `"0"` to install dependencies

# Optional (recomended)
Run command prompt as administrator and cd to litera1n folder, type `cpbin` ~ this allows you to run `litera1n` from anywhere by typing `checkra1n` from cmd

# Steps
For the menu, simply follow installation
for the instant checkra1n cd to the folder and type `cpbin.lnk` (allows you to just type checkra1n from anywhere, boot flags not supported yet)
For a bad GUI version cd to the folder and type `python gui.py`

# Installation:
```
git clone https://github.com/BananeRapeuse/litera1n/
cd litera1n
python main.py
```

# Features
- Gui
- Cli
- DFU tool ~ `python dfu.py`
- Menu
- Open source

# TO DO:
- [ ] Make the GUI better

# Compatability

- iPhone: iPhone 4s --> iPhone X
- iPad: iPad 2 --> iPad 7th gen
- iPod Touch: iPod 5th gen --> iPod 7th gen

# Troubleshooting:
1. restart your computer at least 3 times after installing drivers
2. re-try the jailbreak

# Errors:
 **1.** File "C:\Users\users\Downloads\ipwndfu-master\ipwndfu-master\ipwndfu", line 47, in <module>
    device = dfu.acquire_device()
  File "C:\Users\users\Downloads\ipwndfu-master\ipwndfu-master\dfu.py", line 16, in acquire_device
    for device in usb.core.find(find_all=True, idVendor=0x5AC, idProduct=0x1227, backend=backend):
  File "C:\Users\users\Downloads\ipwndfu-master\ipwndfu-master\usb\core.py", line 1263, in find
    raise NoBackendError('No backend available')
usb.core.NoBackendError: No backend available
 
 
(also remember to install python with this error)

_with this error you must read the #must do section_

# Credits:
- [axi0mX](https://github.com/axi0mx) for the checkm8 exploit
- [Kim Jong Cracks](https://github.com/KJCracks) for checkra1n
 
 # Disclaimer
 We are not responsible for your device errors, or any data loosing/corrupting, ...
