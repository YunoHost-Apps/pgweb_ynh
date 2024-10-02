<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Pgweb voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![Pgweb met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Pgweb snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 0.16.1~ynh2

**Demo:** <https://pgweb-demo.fly.dev/>

## Schermafdrukken

![Schermafdrukken van Pgweb](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele website van de app: <https://sosedoff.github.io/pgweb/>
- Upstream app codedepot: <https://github.com/sosedoff/pgweb>
- YunoHost-store: <https://apps.yunohost.org/app/pgweb>
- Meld een bug: <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
of
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
