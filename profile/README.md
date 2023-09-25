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

