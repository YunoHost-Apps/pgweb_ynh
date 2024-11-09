<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Pgweb pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/pgweb.svg)](https://ci-apps.yunohost.org/ci/apps/pgweb/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/pgweb.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/pgweb.maintain.svg)

[![Installer Pgweb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pgweb)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Pgweb rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Pgweb est un explorateur de bases de données Web pour PostgreSQL, écrit en Go. Distribué sous forme de binaire simple sans aucune dépendance. Très facile à utiliser et offre juste la bonne quantité de fonctionnalités.

### Fonctionnalités

- Aucune dépendance.
- Fonctionne avec PostgreSQL 9.1+.
- Prend en charge les tunnels SSH natifs.
- Plusieurs sessions de base de données.
- Exécutez et analysez des requêtes SQL personnalisées.
- Exportation de données de table et de requête au format CSV/JSON/XML.
- Historique des requêtes.
- Signets du serveur.


**Version incluse :** 0.16.2~ynh1

**Démo :** <https://pgweb-demo.fly.dev/>

## Captures d’écran

![Capture d’écran de Pgweb](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://sosedoff.github.io/pgweb/>
- Dépôt de code officiel de l’app : <https://github.com/sosedoff/pgweb>
- YunoHost Store : <https://apps.yunohost.org/app/pgweb>
- Signaler un bug : <https://github.com/YunoHost-Apps/pgweb_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade pgweb -u https://github.com/YunoHost-Apps/pgweb_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
