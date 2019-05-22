mkiso
=====

Make a custom CentOS 7 iso with optional kickstart, config, and volume name.

Usage
-----

```
  sudo ./cent-mkiso [-k KICKSTART] [-c ISOLINUX_CONFIG] [-v VOLUME_NAME] [-u]
```

Dependancies
------------

* `mkisofs` (from `genisoimage` on Ubuntu)
* `curl`
* `isohybrid` (from `syslinux-utils` on Ubuntu) if you want to build ISOs 
  for use on a usb stick.

TODO
----

* flag, config, or environmental variable for mirror.
* update mirror in kickstart
* Makefile install
