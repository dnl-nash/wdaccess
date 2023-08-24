WDAccess
This script, executed under sudo, will install and set up the waydroid container for android apps. This script will modify the projects images to allow for native translation of arm/arm64 instructions executed by apps to x86/x86_64 equivalents. The script will also install the talkback screen reader, espeak TTS engine, and support for google services such as the play store.
Several options, added and combined through different basenames and separated by ., are possible:
nogoogle: installs a version of the system and vendor image without GMS support
nodesktop: does not start android on desktop login
notrans: does not install arm translation support
notermux: does not attempt to install termux for ssh support
noinit: does not clear images that may already be present
