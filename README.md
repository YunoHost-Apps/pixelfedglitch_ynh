<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Pixelfed for YunoHost

[![Integration level](https://dash.yunohost.org/integration/pixelfed.svg)](https://ci-apps.yunohost.org/ci/apps/pixelfed/) ![Working status](https://ci-apps.yunohost.org/ci/badges/pixelfed.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/pixelfed.maintain.svg)

[![Install Pixelfed with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pixelfed)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Pixelfed quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

PixelFed is a decentralized and federated image sharing software under development.
In addition to taking over the functionality of Instagram, the functioning of PixelFed is:

* Decentralized: Each instance can follow one or more other PixelFed instances in order to allow their respective members to interact. A first pixelfed.social public body limited to 10,000 members has already been created.

* Federated: Via the ActivityPub protocol, PixelFed can interact with other software that is part of the Fediverse, such as Mastodon or PeerTube for example.

It is also possible to import your data from Instagram.


**Shipped version:** 0.12.3~ynh3

## Screenshots

![Screenshot of Pixelfed](./doc/screenshots/screenshots.jpg)

## Documentation and resources

- Official app website: <https://pixelfed.org/>
- Official user documentation: <https://docs.pixelfed.org/>
- Official admin documentation: <https://docs.pixelfed.org/running-pixelfed/administration.html>
- Upstream app code repository: <https://github.com/pixelfed/pixelfed>
- YunoHost Store: <https://apps.yunohost.org/app/pixelfed>
- Report a bug: <https://github.com/YunoHost-Apps/pixelfed_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/pixelfed_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pixelfed_ynh/tree/testing --debug
or
sudo yunohost app upgrade pixelfed -u https://github.com/YunoHost-Apps/pixelfed_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
