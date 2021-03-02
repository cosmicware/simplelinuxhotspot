# simplelinuxhotspot
Deploy a simple access on a linux device

## Hardware requirements:
    It is recommened the user has two network interfaces 
    One of those interface will act as a hotspot interface
    The other interface will provide internet acccess to the hotspot interface
    Both interface can be wirless so there is no need for an ethernet cable (providing one of the interface support AP mode)

## Install the tool dependencies:
    Step 1. sudo apt update
    Step 2. sudo apt upgrade
    Step 3. sudo apt install hostapd
    Step 4. sudo apt install dnsmasq
    Step 5. sudo apt install g++
    
## Set hotspot values:
    Step 1: the user will need to provide values for some variables such as
    hotspot interface, ssid and password etc. This is done within the source code.
 
## Compile and execute the tool:
    Step 1. sudo g++ slh.cpp -o slh
    Step 2. sudo ./slh
