<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# OSjs pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/osjs.svg)](https://dash.yunohost.org/appci/app/osjs) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/osjs.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/osjs.maintain.svg)

[![Installer OSjs avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osjs)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer OSjs rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

OS.js est une plate-forme de bureau Web open source avec un gestionnaire de fenêtres, des API d'application, une boîte à outils GUI, des abstractions de système de fichiers et bien plus encore.


**Version incluse :** 3.1.12~ynh3

**Démo :** <https://demo.os-js.org/>

## Captures d’écran

![Capture d’écran de OSjs](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.

## Documentations et ressources

- Site officiel de l’app : <https://www.os-js.org>
- Documentation officielle de l’admin : <https://manual.os-js.org/>
- Dépôt de code officiel de l’app : <https://github.com/os-js/OS.js>
- YunoHost Store : <https://apps.yunohost.org/app/osjs>
- Signaler un bug : <https://github.com/YunoHost-Apps/osjs_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/osjs_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
ou
sudo yunohost app upgrade osjs -u https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
