# Húsvætti (husvaetti)
From faroese [Sprotin](https://sprotin.fo) :

> *  skordýr av ættini Tineidae, í Føroyum eru trý sløg av húsvættum: húsvættið brúna, húsvættið gráa og húsvættið 
     svarta; dreingirnir fylktust um hana sum húsvætti um ljósið.

Usually it means an insect of the type: Tineidae. But the word uses the faroese word hús, which means house and
the faroese word vætti, which can mean poor or miserable creature; boor, oaf, rude fellow. 

I have choosen to name my home-assistant installation Húsvætti, because it should be a house boor that just automates my
house without too much hassle.

## Work log
This section works as a work log for my setup.

### 2021-11-20
Installed Home Assistant 2021.11.4 on my home instance. As part of the setup I've installed [AdGuard Home](https://github.com/hassio-addons/addon-adguard-home),
[VSCode Server](https://github.com/hassio-addons/addon-vscode) and setup GIT to fetch the configuration files.

* Steps are : setup SSH key
* https://peyanski.com/automatic-home-assistant-backup-to-github/#Pushing_all_changes_to_GitHub_manually
* Install HACS
  * wget -O - https://get.hacs.xyz | bash -
  * Add integration HACS

The challenge now is to setup the internal workings of the network and to identify the key components. The inital key 
components are the 

* WAN - The Wide Area Network is provided by the local internet provider. The modem is also provided by them and as such 
  is not considered safe.
* FIREWALL
* DHCP - The initial setup has a single DHCP and this aims to separate the devices based on IP ranges and functions.
  The plan is to 
* DNS


## Active Integrations

- Beoplay
- Met.no
- HACS

## Setup
This section focuses on the setup of the devices and as with all things, this is a natural progression through
time. Therefor this captures the history of the setup of Húsvætti.

## [2021-11-09 - v0.0.2]

- Added Calendar integration to both work and home calenders.
- Added Met.no integration and created a Weather Tile in the TileBoard.
- Added WorldClock integration and setup clock for Greenland, Faroe Island and Denmark.
- Installed HACS into the docker image:
     - Run the command: ```docker exec -it husvaetti bash```
     - Inside the docker image run the command: ```wget -O - https://get.hacs.xyz | bash -```
     - Install the HACS through the Integrations Panel ([see more](https://hacs.xyz/)).

## [2021-11-09 - v0.0.1]

- Added Apple TV to the setup.
- Used the custom_components/apple-airplayer to add all AirPlay devices to the setup