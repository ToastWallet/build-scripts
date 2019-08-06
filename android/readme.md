# Android APK Build Script
## Requirements
 - npm
 - git
 - zip
 - pcregrep
 - android studio
 - a java keystore file containing your signing certificate for app store uploading (if you want code signing)

This has been tested on macOS 10.14.5, theoretically it should also work on gitbash or linux 

## Usage

 1. Copy the script somewhere.
 2. Copy your keystore file into the same folder.
 3. ./androidbuild [your keystore file]
 4. The script will inform you where to find your build

