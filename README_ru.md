<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# PrivateBin для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/privatebin)](https://ci-apps.yunohost.org/ci/apps/privatebin/)
![Состояние работы](https://apps.yunohost.org/badge/state/privatebin)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/privatebin)

[![Установите PrivateBin с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить PrivateBin быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**Поставляемая версия:** 1.7.5~ynh3

**Демо-версия:** <https://privatebin.net/>

## Снимки экрана

![Снимок экрана PrivateBin](./doc/screenshots/bootstrap.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://privatebin.info/>
- Официальная документация администратора: <https://github.com/PrivateBin/PrivateBin/wiki>
- Репозиторий кода главной ветки приложения: <https://github.com/PrivateBin/PrivateBin>
- Магазин YunoHost: <https://apps.yunohost.org/app/privatebin>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
или
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
