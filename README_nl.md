<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Nextcloud voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/nextcloud)](https://ci-apps.yunohost.org/ci/apps/nextcloud/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/nextcloud)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/nextcloud)

[![Nextcloud met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nextcloud)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Nextcloud snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Nextcloud lets you access and synchronize data, files, contacts and calendars between different devices (PCs or mobiles), or share them with other people (with or without accounts), and also offers advanced communication and collaborative working features. Nextcloud features its own application mechanism (see also [Nextcloud's app store](https://apps.nextcloud.com/)) for specific functionalities. 

In the context of YunoHost, Nextcloud integrates with the SSO/User Portal (YunoHost accounts are automatically connected to Nextcloud).

The `/.well-known` address will be automatically configured for CalDAV and CardDAV synchronization if no other service such as Baïkal is already using it.

The YunoHost catalog has two collaborative office suites, [OnlyOffice](https://github.com/YunoHost-Apps/onlyoffice_ynh) and [Collabora](https://github.com/YunoHost-Apps/collabora_ynh), which can be integrated with Nextcloud.

**Geleverde versie:** 30.0.8~ynh1

**Demo:** <https://demo.nextcloud.com/>

## Schermafdrukken

![Schermafdrukken van Nextcloud](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://nextcloud.com>
- Officiele gebruikersdocumentatie: <https://docs.nextcloud.com/server/latest/user_manual/en/>
- Officiele beheerdersdocumentatie: <https://docs.nextcloud.com/server/stable/admin_manual/>
- Upstream app codedepot: <https://github.com/nextcloud/server>
- YunoHost-store: <https://apps.yunohost.org/app/nextcloud>
- Meld een bug: <https://github.com/YunoHost-Apps/nextcloud_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing --debug
of
sudo yunohost app upgrade nextcloud -u https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
