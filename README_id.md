<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# PrivateBin untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/privatebin.svg)](https://ci-apps.yunohost.org/ci/apps/privatebin/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/privatebin.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/privatebin.maintain.svg)

[![Pasang PrivateBin dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang PrivateBin secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Versi terkirim:** 1.7.4~ynh3

**Demo:** <https://privatebin.net/>

## Tangkapan Layar

![Tangkapan Layar pada PrivateBin](./doc/screenshots/bootstrap.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://privatebin.info/>
- Dokumentasi admin resmi: <https://github.com/PrivateBin/PrivateBin/wiki>
- Depot kode aplikasi hulu: <https://github.com/PrivateBin/PrivateBin>
- Gudang YunoHost: <https://apps.yunohost.org/app/privatebin>
- Laporkan bug: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
atau
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
