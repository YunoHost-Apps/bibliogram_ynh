<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Bibliogram for YunoHost

[![Integration level](https://dash.yunohost.org/integration/bibliogram.svg)](https://dash.yunohost.org/appci/app/bibliogram) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.maintain.svg)  
[![Install Bibliogram with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bibliogram)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Bibliogram quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Bibliogram works without browser JavaScript, has no ads or tracking, and doesn't urge you to sign up.


**Shipped version:** 1.0.0~ynh8

**Demo:** https://bibliogram.art/

## Screenshots

![](./doc/screenshots/bibliogram.jpg)

## Disclaimers / important information

## Configuration

Bibliogram requires dedicated domain like `bibliogram.domain.tld`.  
You can configure Bibliogram by editing this file `/var/www/bibliogram/config.js` using this the [documentation](https://git.sr.ht/~cadence/bibliogram-docs/tree/master/docs/Configuring.md)

## Documentation and resources

* Official admin documentation: https://git.sr.ht/~cadence/bibliogram-docs
* Upstream app code repository: https://git.sr.ht/~cadence/bibliogram
* YunoHost documentation for this app: https://yunohost.org/app_bibliogram
* Report a bug: https://github.com/YunoHost-Apps/bibliogram_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
or
sudo yunohost app upgrade bibliogram -u https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps