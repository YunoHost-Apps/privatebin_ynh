<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# PrivateBin para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/privatebin)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/privatebin)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/privatebin)

[![Instalar PrivateBin con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar PrivateBin de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Versión proporcionada:** 1.7.5~ynh2

**Demo:** <https://privatebin.net/>

## Capturas de pantalla

![Captura de pantalla de PrivateBin](./doc/screenshots/bootstrap.png)

## Documentación e recursos

- Web oficial da app: <https://privatebin.info/>
- Documentación oficial para admin: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repositorio de orixe do código: <https://github.com/PrivateBin/PrivateBin>
- Tenda YunoHost: <https://apps.yunohost.org/app/privatebin>
- Informar dun problema: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
ou
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
