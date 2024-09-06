<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Pgweb YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![Instalatu Pgweb YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Pgweb YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 0.16.0~ynh1

**Demoa:** <https://pgweb-demo.fly.dev/>

## Pantaila-argazkiak

![Pgweb(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://sosedoff.github.io/pgweb/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/sosedoff/pgweb>
- YunoHost Denda: <https://apps.yunohost.org/app/pgweb>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
edo
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
