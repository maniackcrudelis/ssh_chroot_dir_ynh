# ssh chroot directory pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/ssh_chroot_dir.svg)](https://dash.yunohost.org/appci/app/ssh_chroot_dir) ![](https://ci-apps.yunohost.org/ci/badges/ssh_chroot_dir.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/ssh_chroot_dir.maintain.svg)  
[![Installer ssh chroot directory avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=ssh_chroot_dir)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer ssh chroot directory rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

This app create a directory for an user, to allow him to put in here his backups (or whatever he want).  
This directory is accessible by ssh or sftp.  
The directory is highly secured by a complete chroot with limited commands available. So the user can't go out of his directory and can't use any other command which not allowed.  
In addition to the chroot, the user has a limited space available.

So, you can provide to a distant user a limited part of your hard disk to let him put his backup, without any risk for your own server.


**Version incluse :** 1.2~ynh4



## Documentations et ressources

* Site officiel de l'app : https://github.com/maniackcrudelis/ssh_chroot
* Dépôt de code officiel de l'app : https://github.com/maniackcrudelis/ssh_chroot
* Documentation YunoHost pour cette app : https://yunohost.org/app_ssh_chroot_dir
* Signaler un bug : https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/tree/testing --debug
ou
sudo yunohost app upgrade ssh_chroot_dir -u https://github.com/YunoHost-Apps/ssh_chroot_dir_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps