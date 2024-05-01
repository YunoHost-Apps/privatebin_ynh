<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 的 PrivateBin

[![集成程度](https://dash.yunohost.org/integration/privatebin.svg)](https://dash.yunohost.org/appci/app/privatebin) ![工作状态](https://ci-apps.yunohost.org/ci/badges/privatebin.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/privatebin.maintain.svg)

[![使用 YunoHost 安装 PrivateBin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=privatebin)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 PrivateBin。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Minimalist pastebin where the server has zero knowledge of pasted data. Data is encrypted/decrypted in the browser using 256bit AES in Galois Counter mode.


**分发版本：** 1.7.1~ynh1

**演示：** <https://privatebin.net/>

## 截图

![PrivateBin 的截图](./doc/screenshots/bootstrap.png)

## 文档与资源

- 官方应用网站： <https://privatebin.info/>
- 官方管理文档： <https://github.com/PrivateBin/PrivateBin/wiki>
- 上游应用代码库： <https://github.com/PrivateBin/PrivateBin>
- YunoHost 商店： <https://apps.yunohost.org/app/privatebin>
- 报告 bug： <https://github.com/YunoHost-Apps/privatebin_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
或
sudo yunohost app upgrade privatebin -u https://github.com/YunoHost-Apps/privatebin_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
