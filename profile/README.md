# ᴡᴇʟᴄᴏᴍᴇ ᴛᴏ ᴇᴛʜᴇʀᴇᴀʟ ᴘʀᴏᴊᴇᴄᴛ

WORK IN PROGRESS | DO NOT FORK


<p align="center">
<img src="https://github.com/Ethereal-OS/Manifest/blob/A13/assists/ETHEREAL-OS.png" > 
</p>

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
      repo init -u https://github.com/Ethereal-OS/Manifest -b A13

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
coder28@sbi
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

If you got some commits missing in our sources for your device, let us know on our telegram chat. Everything else, it's up to you at the time of building.

Credits
-------
* [**ArrowOS Project**](https://github.com/ArrowOS)
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Project-Xtended**](https://github.com/Project-Xtended/)
* [**Colt Enigma**](https://github.com/Colt-Enigma)
* [**VoidUI**](https://github.com/VoidUI-Tiramisu/)
* [**Thanks to all the custom rom community**]

# Thanks & Regards 

<pre> 88888888b d888888P dP     dP   88888888b  888888ba   88888888b  .d888888  dP                  .88888.  .d88888b  
 88           88    88     88   88         88    `8b  88        d8'    88  88                 d8'   `8b 88.    "' 
a88aaaa       88    88aaaaa88a a88aaaa    a88aaaa8P' a88aaaa    88aaaaa88a 88                 88     88 `Y88888b. 
 88           88    88     88   88         88   `8b.  88        88     88  88        88888888 88     88       `8b 
 88           88    88     88   88         88     88  88        88     88  88                 Y8.   .8P d8'   .8P 
 88888888P    dP    dP     dP   88888888P  dP     dP  88888888P 88     88  88888888P           `8888P'   Y88888P  
                                                                                                                  
                                                                                                                  </pre>





