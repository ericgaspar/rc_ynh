# RocketChat pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/rocketchat.svg)](https://dash.yunohost.org/appci/app/rocketchat) ![](https://ci-apps.yunohost.org/ci/badges/rocketchat.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/rocketchat.maintain.svg)  
[![Installer RocketChat avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=rocketchat)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer RocketChat rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
RocketChat est une plate-forme de collaboration de chat d'équipe gratuite et open source qui permet aux utilisateurs de communiquer en toute sécurité en temps réel sur les appareils sur le Web, le bureau ou le mobile et de personnaliser leur interface avec une gamme de plugins, de thèmes et d'intégrations avec d'autres logiciels clés.

**Version incluse :** 3.7.1

## Captures d'écran

![](https://rocket.chat/wp-content/uploads/2020/07/devices-screens-768x433.png.webp)

## Démo

* [Démo officielle](https://cloud.rocket.chat/trial/)

## Configuration

Comment configurer cette application : via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle : https://docs.rocket.chat/
 * Documentation YunoHost : If specific documentation is needed, feel free to contribute.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ?
* L'application peut-elle être utilisée par plusieurs utilisateurs ?

#### Architectures supportées

* x86-64 - [![](https://ci-apps.yunohost.org/ci/logs/rocketchat%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/rocketchat/)
* ARMv8-A - [![](https://ci-apps-arm.yunohost.org/ci/logs/rocketchat%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/rocketchat/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations que vous souhaitez ajouter sur cette application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/rocketchat_ynh/issues
 * Site de l'application : https://rocket.chat/
 * Dépôt de l'application principale : https://github.com/RocketChat/Rocket.Chat
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/rocketchat_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/rocketchat_ynh/tree/testing --debug
or
sudo yunohost app upgrade rocketchat -u https://github.com/YunoHost-Apps/rocketchat_ynh/tree/testing --debug
```
