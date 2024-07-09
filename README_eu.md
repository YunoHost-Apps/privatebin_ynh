<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# PrivateBin YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/privatebin.svg)](https://ci-apps.yunohost.org/ci/apps/privatebin/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/privatebin.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/privatebin.maintain.svg)

[![Instalatu PrivateBin YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek PrivateBin YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Paketatutako bertsioa:** 1.7.4~ynh1

**Demoa:** <https://privatebin.net/>

## Pantaila-argazkiak

![PrivateBin(r)en pantaila-argazkia](./doc/screenshots/bootstrap.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://privatebin.info/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/PrivateBin/PrivateBin/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/PrivateBin/PrivateBin>
- YunoHost Denda: <https://apps.yunohost.org/app/privatebin>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
edo
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
