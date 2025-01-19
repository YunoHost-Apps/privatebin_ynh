<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# PrivateBin dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/privatebin)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
![Status działania](https://apps.yunohost.org/badge/state/privatebin)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/privatebin)

[![Zainstaluj PrivateBin z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację PrivateBin na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Dostarczona wersja:** 1.7.5~ynh3

**Demo:** <https://privatebin.net/>

## Zrzuty ekranu

![Zrzut ekranu z PrivateBin](./doc/screenshots/bootstrap.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://privatebin.info/>
- Oficjalna dokumentacja dla administratora: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repozytorium z kodem źródłowym: <https://github.com/PrivateBin/PrivateBin>
- Sklep YunoHost: <https://apps.yunohost.org/app/privatebin>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
lub
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
