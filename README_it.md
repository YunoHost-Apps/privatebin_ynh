<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# PrivateBin per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/privatebin.svg)](https://dash.yunohost.org/appci/app/privatebin) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/privatebin.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/privatebin.maintain.svg)

[![Installa PrivateBin con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare PrivateBin su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Versione pubblicata:** 1.7.1~ynh1

**Prova:** <https://privatebin.net/>

## Screenshot

![Screenshot di PrivateBin](./doc/screenshots/bootstrap.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://privatebin.info/>
- Documentazione ufficiale per gli amministratori: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repository upstream del codice dell’app: <https://github.com/PrivateBin/PrivateBin>
- Store di YunoHost: <https://apps.yunohost.org/app/privatebin>
- Segnala un problema: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
o
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
