<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Glance untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/glance)](https://ci-apps.yunohost.org/ci/apps/glance/)
![Status kerja](https://apps.yunohost.org/badge/state/glance)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/glance)

[![Pasang Glance dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=glance)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Glance secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 0.6.4~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Glance](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://github.com/glanceapp/glance/blob/main/docs/configuration.md>
- Depot kode aplikasi hulu: <https://github.com/glanceapp/glance>
- Gudang YunoHost: <https://apps.yunohost.org/app/glance>
- Laporkan bug: <https://github.com/YunoHost-Apps/glance_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/glance_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
atau
sudo yunohost app upgrade glance -u https://github.com/YunoHost-Apps/glance_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
