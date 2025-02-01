<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# PrivateBin for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/privatebin)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
![Working status](https://apps.yunohost.org/badge/state/privatebin)
![Maintenance status](https://apps.yunohost.org/badge/maintained/privatebin)

[![Install PrivateBin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install PrivateBin quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Shipped version:** 1.7.6~ynh1

**Demo:** <https://privatebin.net/>

## Screenshots

![Screenshot of PrivateBin](./doc/screenshots/bootstrap.png)

## Documentation and resources

- Official app website: <https://privatebin.info/>
- Official admin documentation: <https://github.com/PrivateBin/PrivateBin/wiki>
- Upstream app code repository: <https://github.com/PrivateBin/PrivateBin>
- YunoHost Store: <https://apps.yunohost.org/app/privatebin>
- Report a bug: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
or
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
