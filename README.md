# XBIW
Xbps-install wrapper written in Python that doesn't care about case sensitiveness and package versions.

![xbi](https://raw.githubusercontent.com/Sbatushe/xbi/main/Istantanea_2021-11-12_13-31-56.png)

### Description
This wrapper allows to easily install packages without worrying about software versions and case sensitiveness. This script is totally safe because it will launch xbps-install without the -y option.

### Configure
If you use sudo there's nothing to configure. If you use doas, edit the script and set the superuser value to doas

### FAQ
Q: What will happen if you install a package with different versions?

A: Nothing, because the script can accept only 1 possible version. If versions are more or less, it stops. If you need to install some strange type of software version, just use xbps-install. However, it's very unlikely that you will find a software with different versions.
