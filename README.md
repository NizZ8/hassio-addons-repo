# Marcelveldt's Hass.io Add-ons for Home Assistant

![Project Stage][project-stage-shield]
[![Community Forum][forum-shield]][forum]

## About
I created this repo to store the addons I use and/or created myself but as some add-ons might come in handy for others too I decided to make the repo public.

## Installation

Adding this add-ons repository to your Hass.io Home Assistant instance is
pretty easy. Follow [the official instructions][third-party-addons] on the
website of Home Assistant, and use the following URL:

```txt
https://github.com/NizZ8/hassio-addons-repo
```

## Add-ons provided by this repository

### &#10003; [Playlistsyncer][addon-playlistsyncer]

This addon/docker image will allow you to sync playlists between several streaming services. I created this as a personal project but this might come in handy for others too. Supported streaming services: Spotify, Tidal and Qobuz Special: Also supports Roon (www.roonlabs.com) media software for syncing playlists.


### &#10003; [Radarr][addon-radarr]

A fork of Sonarr to work with movies à la Couchpotato.


### &#10003; [Sonarr][addon-sonarr]

Sonarr (formerly NZBdrone) is a PVR for usenet and bittorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.

### &#10003; [Sonarr_preview][addon-sonarr_preview]

Sonarr (formerly NZBdrone) is a PVR for usenet and bittorrent users. It can monitor multiple RSS feeds for new episodes of your favorite shows and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.

### &#10003; [Ombi][addon-ombi]

Ombi add-on based on the docker image linuxserver/ombi

### &#10003; [Jackett][addon-jackett]

Ombi add-on based on the docker image linuxserver/jackett

## Contributing

This is an active open-source project. Feel free to use the code and/or contribute changes.

[addon-radarr]: https://github.com/NizZ8/hassio-addons-repo/tree/master/radarr
[addon-sonarr]: https://github.com/NizZ8/hassio-addons-repo/tree/master/sonarr
[addon-sonarr_preview]: https://github.com/NizZ8/hassio-addons-repo/tree/master/sonarr_preview
[addon-ombi]: https://github.com/NizZ8/hassio-addons-repo/tree/master/ombi
[addon-jackett]: https://github.com/NizZ8/hassio-addons-repo/tree/master/jackett
[addon-tautulli_host]: https://github.com/NizZ8/hassio-addons-repo/tree/master/tautulli_host


[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/t/repository-marcelveldts-hassio-add-ons/99540
[maintenance-shield]: https://img.shields.io/maintenance/yes/2018.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/
