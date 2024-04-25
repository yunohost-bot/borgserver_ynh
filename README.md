<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Borg Server for YunoHost

[![Integration level](https://dash.yunohost.org/integration/borgserver.svg)](https://dash.yunohost.org/appci/app/borgserver) ![Working status](https://ci-apps.yunohost.org/ci/badges/borgserver.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/borgserver.maintain.svg)

[![Install Borg Server with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=borgserver)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Borg Server quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Offer backup storage to a friend.

The main goal of Borg is to provide an efficient and secure way to backup data. The data deduplication technique used makes Borg suitable for daily backups since only changes are stored. The authenticated encryption technique makes it suitable for backups to not fully trusted targets.


**Shipped version:** 1.2.8~ynh1
## Documentation and resources

- Official app website: <https://www.borgbackup.org/>
- Official admin documentation: <https://borgbackup.readthedocs.io/en/stable/>
- Upstream app code repository: <https://github.com/borgbackup/borg>
- YunoHost Store: <https://apps.yunohost.org/app/borgserver>
- Report a bug: <https://github.com/YunoHost-Apps/borgserver_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/borgserver_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/borgserver_ynh/tree/testing --debug
or
sudo yunohost app upgrade borgserver -u https://github.com/YunoHost-Apps/borgserver_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
