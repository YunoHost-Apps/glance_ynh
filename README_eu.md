<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Glance YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/glance.svg)](https://ci-apps.yunohost.org/ci/apps/glance/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/glance.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/glance.maintain.svg)

[![Instalatu Glance YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glance)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Glance YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 0.6.0~ynh1

## Pantaila-argazkiak

![Glance(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://github.com/glanceapp/glance/blob/main/docs/configuration.md>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/glanceapp/glance>
- YunoHost Denda: <https://apps.yunohost.org/app/glance>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/glance_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/glance_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
edo
sudo yunohost app upgrade glance -u https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
