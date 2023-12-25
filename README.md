<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# AdGuard Home for YunoHost

[![Integration level](https://dash.yunohost.org/integration/adguardhome.svg)](https://dash.yunohost.org/appci/app/adguardhome) ![Working status](https://ci-apps.yunohost.org/ci/badges/adguardhome.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/adguardhome.maintain.svg)

[![Install AdGuard Home with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adguardhome)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install AdGuard Home quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up, it'll cover ALL your home devices, and you don't need any client-side software for that.

It operates as a DNS server that re-routes tracking domains to a "black hole", thus preventing your devices from connecting to those servers. It's based on software we use for our public AdGuard DNS servers -- both share a lot of common code.


**Shipped version:** 0.107.43~ynh2

## Screenshots

![Screenshot of AdGuard Home](./doc/screenshots/68747470733a2f2f63646e2e616467756172642e636f6d2f7075626c69632f416467756172642f436f6d6d6f6e2f616467756172645f686f6d652e676966.gif)

## Documentation and resources

* Official app website: <https://adguard.com/adguard-home.html>
* Official user documentation: <https://kb.adguard.com/en>
* Official admin documentation: <https://github.com/AdguardTeam/AdGuardHome/wiki>
* Upstream app code repository: <https://github.com/AdguardTeam/AdGuardHome>
* YunoHost Store: <https://apps.yunohost.org/app/adguardhome>
* Report a bug: <https://github.com/YunoHost-Apps/adguardhome_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/adguardhome_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/adguardhome_ynh/tree/testing --debug
or
sudo yunohost app upgrade adguardhome -u https://github.com/YunoHost-Apps/adguardhome_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
