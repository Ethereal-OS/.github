# ᴡᴇʟᴄᴏᴍᴇ ᴛᴏ ᴇᴛʜᴇʀᴇᴀʟ ᴘʀᴏᴊᴇᴄᴛ

<p align="center">
<img src="https://github.com/Ethereal-OS/Manifest/blob/A14/assists/ETHEREAL-OS.png" > 
</p>

## Security Patch Levels

| Android Version | Ethereal Version | Security Patch Level |
|------------------|-----------------------|-----------------------|
| Android 13       | AURA | 1 APRIL 2025 |
| Android 14       | ELEGANCE | 1 APRIL 2025 |

## Download Now
<a href="https://sourceforge.net/projects/ethereal-os/files"><img alt="Download Ethereal-OS" src="https://a.fsdn.com/con/app/sf-download-button" width=276 height=48 srcset="https://a.fsdn.com/con/app/sf-download-button?button_size=2x 2x"></a>

## HOW TO BUILD

```
# Make directory for the repo binary

      $ mkdir ~/bin

# Add directory for the repo binary to its path

      $ PATH=~/bin:$PATH

# Downloading repo binary and placing it in the proper directory

      $ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo

# Giving the repo binary the proper permissions

      $ chmod a+x ~/bin/repo

# Initialize Local Repo
      repo init -u https://github.com/Ethereal-OS/Manifest -b A13 --git-lfs

# Sync
      repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

# Build
# Set up environment
      $ . build/envsetup.sh

# Choose a target
      $ lunch ethereal_$device-userdebug

# Build the code
      $ mka bacon -j$(nproc --all)

```
## FUNDING


- UPI ID :  
```
iamcod3x@upi
```

- Bitcoin (BTC):  
```
bc1qmxdtgaw23xmqg3awlfttj7jsnvqld4n5lw3exz
```

- PayPal:
```
https://www.paypal.me/IamCODER
```
- Buy me a Coffee: 
```
https://www.buymeacoffee.com/iamcoder
```
- Buy Me A KO-FI:
```
https://ko-fi.com/iamcod3x
```

Help from other devices for making them Official
------------------------------------------------
##  How to become an Official Maintainer
Make sure you can follow our [rules-and-guidelines](https://github.com/Ethereal-OS/docs/rules-and-guidelines), then if all is right, just message IamCOD3X over [Telegram](https://telegram.me/IamCOD3X) with the device you want to maintain.

-----------------------------------------------
If you got some commits missing in our sources for your device, let us know on our telegram chat. Everything else, it's up to you at the time of building.

Credits
-------
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**VoidUI**](https://github.com/VoidUI-Tiramisu/)
* [**VoltageOS**](https://github.com/VoltageOS)
* [**Thanks to all the custom rom community**]

# Thanks & Regards 

<pre> 88888888b d888888P dP     dP   88888888b  888888ba   88888888b  .d888888  dP                     .88888.  .d88888b  
 88           88    88     88   88         88    `8b  88        d8'    88  88                    d8'   `8b 88.    "' 
a88aaaa       88    88aaaaa88a a88aaaa    a88aaaa8P' a88aaaa    88aaaaa88a 88                    88     88 `Y88888b. 
 88           88    88     88   88         88   `8b.  88        88     88  88        88888888    88     88       `8b 
 88           88    88     88   88         88     88  88        88     88  88                    Y8.   .8P d8'   .8P 
 88888888P    dP    dP     dP   88888888P  dP     dP  88888888P 88     88  88888888P              `8888P'   Y88888P  
                                                                                                                     
                                                                                                                     </pre>





