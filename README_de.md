<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# Pixelfed Glitch für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/pixelfed_glitch)](https://ci-apps.yunohost.org/ci/apps/pixelfed_glitch/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/pixelfed_glitch)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/pixelfed_glitch)

[![Pixelfed Glitch mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=pixelfed_glitch)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie Pixelfed Glitch schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

PixelFed Glitch s a decentralized and federated image sharing software under development. It is a fork of the officiel Pixelfed software.
In addition to taking over the functionality of Instagram, the functioning of PixelFed is:

* Decentralized: Each instance can follow one or more other PixelFed instances in order to allow their respective members to interact. A first pixelfed.social public body limited to 10,000 members has already been created.

* Federated: Via the ActivityPub protocol, PixelFed can interact with other software that is part of the Fediverse, such as Mastodon or PeerTube for example.

It is possible to import your data from Instagram.


**Ausgelieferte Version:** 0.12.4+glitch.1.10.1~ynh1

## Bildschirmfotos

![Bildschirmfotos von Pixelfed Glitch](./doc/screenshots/screenshot.png)

## Dokumentation und Ressourcen

- Offizielle Website der App: <https://pixelfed-glitch.github.io/docs/>
- Offizielle Benutzerdokumentation: <https://pixelfed-glitch.github.io/docs/>
- Offizielle Verwaltungsdokumentation: <https://pixelfed-glitch.github.io/docs/>
- Upstream App Repository: <https://github.com/pixelfed-glitch/pixelfed>
- YunoHost-Shop: <https://apps.yunohost.org/app/pixelfed_glitch>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/pixelfed_glitch_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/pixelfed_glitch_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/pixelfed_glitch_ynh/tree/testing --debug
oder
sudo yunohost app upgrade pixelfed_glitch -u https://github.com/YunoHost-Apps/pixelfed_glitch_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>
