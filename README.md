![discord logo](discord-logo-wordmark.png)

# Discord rpm
Unofficial RPM package for Discord.

## How to use
Open a terminal and run `./create-package.sh stable` to get the stable version of Discord. Replace `stable` by `canary` to get the beta version.

## Features
- Downloads the latest version of Discord from the official website
- Creates a ready-to-use RPM package
- Discord stable and canary can be installed at the same time
- Adds Discord to the applications' list with a nice HD icon
- Supports Fedora (26, 27) and OpenSUSE (Leap)

## More informations

### Warning - no accents

The path where you run the script must **not** contain any special character like é, ü, etc. This is a limitation of the rpm tools.

### How to update

When a new version of discord is released, simply run the script again to get the updated version.

### Requirements
The `rpmdevtools` package is required to build RPM packages. The script detects if it isn't installed and offers to install it.

### About root privileges
Building an RPM package with root privileges is dangerous, see http://serverfault.com/questions/10027/why-is-it-bad-to-build-rpms-as-root.

## Screenshot
![beautiful screenshot](screenshot.png)
