<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Glance

[![集成程度](https://dash.yunohost.org/integration/glance.svg)](https://ci-apps.yunohost.org/ci/apps/glance/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/glance.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/glance.maintain.svg)

[![使用 YunoHost 安装 Glance](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glance)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Glance。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A self-hosted dashboard that puts all your feeds in one place.

### Various widgets

    RSS feeds
    Subreddit posts
    Weather
    Bookmarks
    Latest YouTube videos from specific channels
    Calendar
    Stocks
    iframe
    Twitch channels & top games
    GitHub releases
    Repository overview
    Site monitor


**分发版本：** 0.6.2~ynh1

## 截图

![Glance 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方管理文档： <https://github.com/glanceapp/glance/blob/main/docs/configuration.md>
- 上游应用代码库： <https://github.com/glanceapp/glance>
- YunoHost 商店： <https://apps.yunohost.org/app/glance>
- 报告 bug： <https://github.com/YunoHost-Apps/glance_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/glance_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
或
sudo yunohost app upgrade glance -u https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
