<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# OSjs untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/osjs)](https://ci-apps.yunohost.org/ci/apps/osjs/)
![Status kerja](https://apps.yunohost.org/badge/state/osjs)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/osjs)

[![Pasang OSjs dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osjs)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang OSjs secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

OS.js is an open-source web desktop platform with a window manager, application APIs, GUI toolkit, filesystem abstractions and much more.


**Versi terkirim:** 3.1.12~ynh3

**Demo:** <https://demo.os-js.org/>

## Tangkapan Layar

![Tangkapan Layar pada OSjs](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.os-js.org>
- Dokumentasi admin resmi: <https://manual.os-js.org/>
- Depot kode aplikasi hulu: <https://github.com/os-js/OS.js>
- Gudang YunoHost: <https://apps.yunohost.org/app/osjs>
- Laporkan bug: <https://github.com/YunoHost-Apps/osjs_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/osjs_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
atau
sudo yunohost app upgrade osjs -u https://github.com/YunoHost-Apps/osjs_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
