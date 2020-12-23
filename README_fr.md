# PrivateBin pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/privatebin.svg)](https://dash.yunohost.org/appci/app/privatebin) ![](https://ci-apps.yunohost.org/ci/badges/privatebin.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/privatebin.maintain.svg)  
[![Installer PrivateBin avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer PrivateBin rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

PrivateBin est un logiciel libre, minimaliste, qui joue le rôle de pastebin (coller-corbeille) où le serveur n'a aucune connaissance des données qu'il stocke.

Les données sont chiffrées et déchiffrées dans le navigateur en utilisant la technologie AES 256bits en mode Galois Counter (GCM).

Ce projet est un fork de ZeroBin, développé à l'origine par Sébastien Sauvage. Il a été ré-écrit pour accepter plus facilement des extensions en rajoutant plus de fonctionnalités. Il reste cependant compatible avec le schéma original de stockage des données Zerobin 0.19. Ainsi toutes les installations peuvent être mises à jour vers ce projet, sans perte de données.

**Version incluse :** 1.3.4

## Captures d'écran

![](https://privatebin.info/img/1.0/bootstrap.png)

## Démo

* [Démo Privatebin](https://privatebin.net/)

## Configuration

## Documentation

 * Documentation officielle : https://github.com/PrivateBin/PrivateBin/wiki
 * Documentation YunoHost : https://yunohost.org/#/app_privatebin_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/privatebin%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/privatebin%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/privatebin/)

## Limitations

## Informations additionnelles

Dans la [documentation de mise à jour](https://github.com/PrivateBin/PrivateBin/wiki/Configuration#zerobincompatibility) de PrivateBin, il est précisé que :

Pour une compatibilité complète avec Zerobin et le déchiffrement de tous les vieux "paste", vous devriez activer cette option. Cependant, ce n'est pas recommandé pour les nouvelles installations car cela affaiblit la sécurité de votre instance PrivateBin.

Ceci signifie que nous avons décidé de supprimer ce répertoire pour permettre la sécurisation des données. Vous pouvez sauvegarder le répertoire 'data', si vous voulez conservez vos données. Mais vous devriez savoir que cela réduit la sécurité de votre application.

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/privatebin_ynh/issues
 * Site de l'application PrivateBin : https://privatebin.info/
 * Dépot de l'application principale : https://github.com/PrivateBin/PrivateBin
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request dans la [branche testing](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
ou
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```
