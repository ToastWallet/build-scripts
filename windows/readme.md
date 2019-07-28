# Windows Build Script
## Requirements

 - Git Bash
 - npm install -g electron-builder@19.19.1
 - p12 code signing certificate (if you want code signing)

Due to various breaking changes between Microsoft's toolchains, electron and electron builder this script only signs appx correctly on electron-builder 19.19.1. Please ensure you use this version if you need a signed appx.

## Usage

 1. Copy the script somewhere.
 2. Copy your p12 code certificate into the same folder.
 3. Open Git Bash and navigate there.
 4. ./winbuild [your certificate password]
 5. Navigate to ./core/platforms/browser/dist for builds

## Notes
You can generate a self-signed certificate for your own builds. Placing a dash for the password and providing no certificate should also work although this hasn't been tested.
