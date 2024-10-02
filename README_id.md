<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Pgweb untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![Pasang Pgweb dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Pgweb secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Pgweb is a web-based database explorer for PostgreSQL, written in Go. Distributed as a simple binary with zero dependencies. Very easy to use and packs just the right amount of features.

### Features

- Zero dependencies.
- Works with PostgreSQL 9.1+.
- Supports native SSH tunnels.
- Multiple database sessions.
- Execute and analyze custom SQL queries.
- Table and query data export to CSV/JSON/XML.
- Query history.
- Server bookmarks.


**Versi terkirim:** 0.16.1~ynh2

**Demo:** <https://pgweb-demo.fly.dev/>

## Tangkapan Layar

![Tangkapan Layar pada Pgweb](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://sosedoff.github.io/pgweb/>
- Depot kode aplikasi hulu: <https://github.com/sosedoff/pgweb>
- Gudang YunoHost: <https://apps.yunohost.org/app/pgweb>
- Laporkan bug: <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
atau
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
