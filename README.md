# QHotspot freeRADIUS2 Management Panel for pfSense 

## Getting Started

**!!! This project is under construction. We are not responsible for any problems that may occur in your system.**

**!!!This branch only install old ghost panel**

### Prerequirements

* Fresh installed pfSense 2.3.x or higher

### Installing

Video Tutorial : https://youtu.be/VHfOwj6Ljn0

Connect to pfSense console with popular SSH Client on SSH 
And run the following command :

```
fetch -o install.sh https://goo.gl/7qBoNX && sh install.sh
```

#####Default Configs
* Default mysql root password is ``qhotspot`` and port ``3306``
* Default mysql freeRADIUS username and password both ``qhotspot`` and remote access allowed.
* Default mysql watchdog cron trigger time is every minute
* Default freeRADIUS2 test username and password both ``test``
* Default freeRADIUS2 mysql test username and password both ``testmysql``
* Default Captive Portal zone name is ``QHOTSPOT``
* Default Unifi Controller port is ``8080 (http)`` & ``8443 (https)`` 


## Roadmap
* ~~Install MySQL 5.6~~
* ~~Install PHP MySQL Extensions~~
* ~~Install freeRADIUS2 package~~
* ~~Install cron package~~
* ~~freeRADIUS2 CA & certificate create~~
* ~~freeRADIUS2 settings~~
* ~~freeRADIUS2 EAP settings~~
* ~~freeRADIUS2 test user create~~
* ~~freeRADIUS2 mysql test user create~~
* ~~pfSense CaptivePortal settings~~
* Logging & Signing of the law of the Republic of Turkey No.5651
* ...[more](https://bitbucket.org/qtechnics/qhotspot/issues?kind=enhancement&kind=proposal)

## Built With
* [PHPStorm](https://www.jetbrains.com/phpstorm/) - Best PHP IDE
* [Git](https://git-scm.com/) - Versioning System
* [GitKraken](https://www.gitkraken.com/) - Best Git GUI
* [pfSense Shell](https://doc.pfsense.org/index.php/Using_the_PHP_pfSense_Shell) - pfSense PHP Shell
* [unifi-pfSense](https://github.com/gozoinks/unifi-pfsense) - UniFi Controller software on pfSense and other FreeBSD systems

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Muzaffer Ali AKYIL** - *Initial work* - [Victorious](https://muzaffer.akyil.net)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Resources & Special Thanks

* [Serdar Bayram - Blog](https://www.serdarbayram.net/)
* [Samet Yılmaz - Blog](http://sametyilmaz.com.tr/)
* [pfSense Forums](https://forum.pfsense.org)
* [freeBSD Forums](https://forums.freebsd.org/)