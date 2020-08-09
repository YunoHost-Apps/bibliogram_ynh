# Bibliogram for YunoHost

[![Integration level](https://dash.yunohost.org/integration/bibliogram.svg)](https://dash.yunohost.org/appci/app/bibliogram) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.maintain.svg)  
[![Install Bibliogram with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=bibliogram)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Bibliogram quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Bibliogram is a website that takes data from Instagram's public profile views and puts it into a friendlier page that loads faster, gives downloadable images, eliminates ads, generates RSS feeds, and doesn't urge you to sign up.

**Shipped version:** 1.0.0

## Screenshots

![](sources/bibliogram.jpg)

## Demo

* [Official demo](https://bibliogram.art/)

## Configuration

Bibliogram requires dedicated domain like `bibliogram.domain.tld`.  
You can configure Bibliogram by editing this file `/var/www/bibliogram/config.js` using this the [documentation](https://git.sr.ht/~cadence/bibliogram-docs/tree/master/docs/Configuring.md)

## Documentation

 * Official documentation: https://git.sr.ht/~cadence/bibliogram-docs
 * YunoHost documentation: https://yunohost.org/#/app_bibliogram

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **No**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/bibliogram%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/bibliogram/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/bibliogram%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/bibliogram/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/bibliogram_ynh/issues
 * Upstream app repository: https://git.sr.ht/~cadence/bibliogram
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
or
sudo yunohost app upgrade bibliogram -u https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
```
