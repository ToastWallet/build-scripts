# Linux AppImage Build Script
## Requirements

 - apt-get (or yum) install phonegap npm nodejs xorriso icnsutils graphicsmagick
 - npm install -g electron-builder@19.19.1
 - p12 code signing certificate (if you want code signing)

This has been tested on Ubuntu 18.04.2 LTS

## Usage

 1. Copy the script somewhere.
 2. Copy your p12 code certificate into the same folder.
 3. ./linuxbuild [your certificate password]
 4. Navigate to ./core/platforms/browser/dist for builds

## Notes
You can generate a self-signed certificate for your own builds. Placing a dash for the password and providing no certificate should also work although this hasn't been tested.
