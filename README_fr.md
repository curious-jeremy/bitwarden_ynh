# Bitwarden pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/bitwarden.svg)](https://dash.yunohost.org/appci/app/bitwarden)  
[![Installer Bitwarden avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=bitwarden)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Bitwarden rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Bitwarden est un gestionnaire de mots de passe open source.

**Version incluse:** 1.14.2

## Points importants à lire avant l'installation

Après l'installation, l'utilisateur admin recevra un e-mail avec le admin_token a utilisé pour accéder à l'administration de Bitwarden https://your.domain.tld/bitwarden/admin.

## Captures d'écran

![](https://bitwarden.com/images/hero.png)

## Démo

* [Démo officielle](https://vault.bitwarden.com/#/register)

## Configuration

Comment configurer cette application: via le panneau d'administration https://bitwarden.domain.tld/admin.

## Documentation

 * Documentation officielle: https://help.bitwarden.com/ et https://github.com/dani-garcia/bitwarden_rs/wiki

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

* L'authentification LDAP et HTTP est-elle prise en charge? **No**
* L'application peut-elle être utilisée par plusieurs utilisateurs? **Yes**

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/bitwarden%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/bitwarden/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/bitwarden%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/bitwarden/)

## Liens

 * Signaler un bug: https://github.com/YunoHost-Apps/bitwarden_ynh/issues
 * Site de l'application: https://bitwarden.com/
 * Dépôt de l'application principale: https://github.com/dani-garcia/bitwarden_rs
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/bitwarden_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/bitwarden_ynh/tree/testing --debug
ou
sudo yunohost app upgrade bitwarden -u https://github.com/YunoHost-Apps/bitwarden_ynh/tree/testing --debug
```
