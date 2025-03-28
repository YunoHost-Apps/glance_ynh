<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Glance для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/glance)](https://ci-apps.yunohost.org/ci/apps/glance/)
![Состояние работы](https://apps.yunohost.org/badge/state/glance)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/glance)

[![Установите Glance с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glance)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Glance быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

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


**Поставляемая версия:** 0.7.8~ynh1

## Снимки экрана

![Снимок экрана Glance](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальная документация администратора: <https://github.com/glanceapp/glance/blob/main/docs/configuration.md>
- Репозиторий кода главной ветки приложения: <https://github.com/glanceapp/glance>
- Магазин YunoHost: <https://apps.yunohost.org/app/glance>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/glance_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/glance_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
или
sudo yunohost app upgrade glance -u https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
