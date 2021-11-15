# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- Change docker image to ghcr.io/home-assistant/raspberrypi3-homeassistant:stable, for more infomation see
[Hassio](https://www.home-assistant.io/installation/raspberrypi#docker-compose).
- Added Linode binary sensors to UI.
- Added [Plex](https://www.plex.tv/media-server-downloads/) to the ```docker-compose.yml```.
- Added [Crypto State](https://github.com/heyajohnny/cryptoinfo), [Crypto Tracker](https://github.com/BigNocciolino/CryptoTracker) 
  and [Mini Graph Card](https://github.com/kalkih/mini-graph-card).

## [2021-11-15]

- Added custom_component [beoplay](https://github.com/giachello/beoplay) to add support for Bang and Olufsen devices.
- Moved [WorldClock](https://www.home-assistant.io/integrations/worldclock/) to packages structure.
- Changed secret naming convention.
- Added theme [kibibit](https://github.com/Kibibit/hass-kibibit-theme)
- Updated [HACS](https://hacs.xyz/) to version 1.17.2.
- Added [Linode](https://www.home-assistant.io/integrations/linode/) to the installation

## [2021-11-09 - v0.0.2]

### Added

- Added configuration for calenders. One for work and one private. The configuration has secret mapping as well.
- Added weather forecast to the TileBoard.
- Added WorldClock sensors for West-Greenland, Faroe Islands and Denmark.

## [2021-11-09 - v0.0.1]

### Added

- Added [TileBoard v2.6.5](https://github.com/resoai/TileBoard/releases/tag/v2.6.5) to www/dash
- Added [Apple AirPlayer v0.0.8](https://github.com/georgezhao2010/apple_airplayer/releases/tag/v0.0.8) to custom_components