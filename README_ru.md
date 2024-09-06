<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Pgweb для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![Установите Pgweb с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Pgweb быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Pgweb is a web-based database explorer for PostgreSQL, written in Go, and works on Mac, Linux and Windows machines. Distributed as a simple binary with zero dependencies. Very easy to use and packs just the right amount of features.

### Features

- Cross-platform: Mac/Linux/Windows (64bit).
- Zero dependencies.
- Works with PostgreSQL 9.1+.
- Supports native SSH tunnels.
- Multiple database sessions.
- Execute and analyze custom SQL queries.
- Table and query data export to CSV/JSON/XML.
- Query history.
- Server bookmarks.


**Поставляемая версия:** 0.16.0~ynh1

**Демо-версия:** <https://pgweb-demo.fly.dev/>

## Снимки экрана

![Снимок экрана Pgweb](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://sosedoff.github.io/pgweb/>
- Репозиторий кода главной ветки приложения: <https://github.com/sosedoff/pgweb>
- Магазин YunoHost: <https://apps.yunohost.org/app/pgweb>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
или
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
