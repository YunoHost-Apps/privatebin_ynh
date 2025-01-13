<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# PrivateBin para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/privatebin)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
![Estado funcional](https://apps.yunohost.org/badge/state/privatebin)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/privatebin)

[![Instalar PrivateBin con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarPrivateBin rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Versión actual:** 1.7.5~ynh1

**Demo:** <https://privatebin.net/>

## Capturas

![Captura de PrivateBin](./doc/screenshots/bootstrap.png)

## Documentaciones y recursos

- Sitio web oficial: <https://privatebin.info/>
- Documentación administrador oficial: <https://github.com/PrivateBin/PrivateBin/wiki>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/PrivateBin/PrivateBin>
- Catálogo YunoHost: <https://apps.yunohost.org/app/privatebin>
- Reportar un error: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
o
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
