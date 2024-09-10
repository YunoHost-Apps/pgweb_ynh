<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Pgweb

[![集成程度](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![使用 YunoHost 安装 Pgweb](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Pgweb。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 0.16.1~ynh1

**演示：** <https://pgweb-demo.fly.dev/>

## 截图

![Pgweb 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://sosedoff.github.io/pgweb/>
- 上游应用代码库： <https://github.com/sosedoff/pgweb>
- YunoHost 商店： <https://apps.yunohost.org/app/pgweb>
- 报告 bug： <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
或
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
