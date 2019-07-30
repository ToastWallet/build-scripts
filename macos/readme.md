# MacOS DMG Build Script
## Requirements

 - git
 - npm install -g electron-builder@19.19.1
 - p12 code signing certificate (if you want code signing)

This has been tested on macOS 10.14.5 

## Usage

 1. Copy the script somewhere.
 2. Copy your p12 code certificate into the same folder.
 3. ./macbuild [your certificate password]
 4. Navigate to ./core/platforms/browser/dist for builds

## Notes
You can generate a self-signed certificate for your own builds. Placing a dash for the password and providing no certificate should also work although this hasn't been tested.
