<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ssh chroot directory for YunoHost

[![Integration level](https://dash.yunohost.org/integration/ssh_chroot_dir.svg)](https://dash.yunohost.org/appci/app/ssh_chroot_dir) ![](https://ci-apps.yunohost.org/ci/badges/ssh_chroot_dir.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ssh_chroot_dir.maintain.svg)  
[![Install ssh chroot directory with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ssh_chroot_dir)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ssh chroot directory quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

This app create a directory for an user, to allow him to put in here his backups (or whatever he want).  
This directory is accessible by ssh or sftp.  
The directory is highly secured by a complete chroot with limited commands available. So the user can't go out of his directory and can't use any other command which not allowed.  
In addition to the chroot, the user has a limited space available.

So, you can provide to a distant user a limited part of your hard disk to let him put his backup, without any risk for your own server.


**Shipped version:** 1.2~ynh4



## Documentation and resources

* Official app website: https://github.com/maniackcrudelis/ssh_chroot
* Upstream app code repository: https://github.com/maniackcrudelis/ssh_chroot
* YunoHost documentation for this app: https://yunohost.org/app_ssh_chroot_dir
* Report a bug: https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/tree/testing --debug
or
sudo yunohost app upgrade ssh_chroot_dir -u https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps