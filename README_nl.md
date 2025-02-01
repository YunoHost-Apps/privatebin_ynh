<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# PrivateBin voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/privatebin)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/privatebin)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/privatebin)

[![PrivateBin met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je PrivateBin snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Geleverde versie:** 1.7.6~ynh1

**Demo:** <https://privatebin.net/>

## Schermafdrukken

![Schermafdrukken van PrivateBin](./doc/screenshots/bootstrap.png)

## Documentatie en bronnen

- Officiele website van de app: <https://privatebin.info/>
- Officiele beheerdersdocumentatie: <https://github.com/PrivateBin/PrivateBin/wiki>
- Upstream app codedepot: <https://github.com/PrivateBin/PrivateBin>
- YunoHost-store: <https://apps.yunohost.org/app/privatebin>
- Meld een bug: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
of
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
