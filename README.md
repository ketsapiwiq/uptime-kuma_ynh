<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Uptime Kuma for YunoHost

[![Integration level](https://dash.yunohost.org/integration/uptime-kuma.svg)](https://ci-apps.yunohost.org/ci/apps/uptime-kuma/) ![Working status](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/uptime-kuma.maintain.svg)

[![Install Uptime Kuma with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=uptime-kuma)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Uptime Kuma quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Uptime Kuma is a self-hosted monitoring tool like "Uptime Robot".

### Features

- Monitoring uptime for HTTP(s) / TCP / Ping / DNS Record / Push.
- Notifications via Telegram, Discord, Gotify, Slack, Pushover, Email (SMTP)...
- 20 second intervals
- Multi Languages
- Simple Status Page
- Ping Chart
- Certificate Info


**Shipped version:** 2.0.0~ynh1

**Demo:** <https://demo.uptime.kuma.pet>

## Screenshots

![Screenshot of Uptime Kuma](./doc/screenshots/example.jpg)

## Documentation and resources

- Official app website: <https://uptime.kuma.pet/>
- Official user documentation: <https://github.com/louislam/uptime-kuma/wiki>
- Upstream app code repository: <https://github.com/louislam/uptime-kuma>
- YunoHost Store: <https://apps.yunohost.org/app/uptime-kuma>
- Report a bug: <https://github.com/YunoHost-Apps/uptime-kuma_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
or
sudo yunohost app upgrade uptime-kuma -u https://github.com/YunoHost-Apps/uptime-kuma_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
