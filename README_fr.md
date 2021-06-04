# Bibliogram pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/bibliogram.svg)](https://dash.yunohost.org/appci/app/bibliogram) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/bibliogram.maintain.svg)  
[![Installer Bibliogram avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=bibliogram)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Bibliogram rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Une interface alternative pour Instagram 

**Version incluse :** 1.0.0~ynh8

**Démo :** https://bibliogram.art/

## Captures d'écran

![](./doc/screenshots/bibliogram.jpg)

## Avertissements / informations importantes

## Configuration

Bibliogram s'installe sur un domaine dédié comme `bibliogram.domain.tld`.  
Vous pouvez configurer Bibliogram en modifiant le fichier `/var/www/bibliogram/config.js` et en vous aidant de la [documentation](https://git.sr.ht/~cadence/bibliogram-docs/tree/master/docs/Configuring.md)

## Documentations et ressources

* Documentation officielle utilisateur : https://yunohost.org/en/app_bibliogram
* Documentation officielle de l'admin : https://git.sr.ht/~cadence/bibliogram-docs
* Dépôt de code officiel de l'app : https://git.sr.ht/~cadence/bibliogram
* Documentation YunoHost pour cette app : https://yunohost.org/app_bibliogram
* Signaler un bug : https://github.com/YunoHost-Apps/bibliogram_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
ou
sudo yunohost app upgrade bibliogram -u https://github.com/YunoHost-Apps/bibliogram_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps