<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Glance for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/glance)](https://ci-apps.yunohost.org/ci/apps/glance/)
![Working status](https://apps.yunohost.org/badge/state/glance)
![Maintenance status](https://apps.yunohost.org/badge/maintained/glance)

[![Install Glance with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glance)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Glance quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

A self-hosted dashboard that puts all your feeds in one place.

### Various widgets

    RSS feeds
    Subreddit posts
    Weather
    Bookmarks
    Latest YouTube videos from specific channels
    Calendar
    Stocks
    iframe
    Twitch channels & top games
    GitHub releases
    Repository overview
    Site monitor


**Shipped version:** 0.7.8~ynh1

## Screenshots

![Screenshot of Glance](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official admin documentation: <https://github.com/glanceapp/glance/blob/main/docs/configuration.md>
- Upstream app code repository: <https://github.com/glanceapp/glance>
- YunoHost Store: <https://apps.yunohost.org/app/glance>
- Report a bug: <https://github.com/YunoHost-Apps/glance_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/glance_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
or
sudo yunohost app upgrade glance -u https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
