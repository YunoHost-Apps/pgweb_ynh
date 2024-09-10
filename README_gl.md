<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Pgweb para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![Instalar Pgweb con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Pgweb de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 0.16.1~ynh1

**Demo:** <https://pgweb-demo.fly.dev/>

## Capturas de pantalla

![Captura de pantalla de Pgweb](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://sosedoff.github.io/pgweb/>
- Repositorio de orixe do código: <https://github.com/sosedoff/pgweb>
- Tenda YunoHost: <https://apps.yunohost.org/app/pgweb>
- Informar dun problema: <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
