![Total downloads](https://img.shields.io/github/downloads/bearsampp/modules-untouched/total.svg?style=flat-square)

This a sub-repo of [Bearsampp project](https://github.com/bearsampp/bearsampp) involving mirror of all modules binaries untouched from their original locations.<br />
There are hosted on Github to prevent dead links.<br />
Binaries files that are not available as archives artefacts or single file are rebuild for bearsampp but original files are included too.<br />
Issues must be reported on [Bearsampp repository](https://github.com/bearsampp/bearsampp/issues).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Adminer](#adminer)
- [Apache](#apache)
- [Composer](#composer)
- [ConsoleZ](#consolez)
- [Filezilla Server](#filezilla-server)
- [Ghostscript](#ghostscript)
- [Git](#git)
- [Gitlist](#gitlist)
- [MailHog](#mailhog)
- [MariaDB](#mariadb)
- [Memcached](#memcached)
- [MongoDB](#mongodb)
- [MySQL](#mysql)
- [Nginx](#nginx)
- [ngrok](#ngrok)
- [Node.js](#nodejs)
- [Perl](#perl)
- [PHP](#php)
- [phpMemAdmin](#phpmemadmin)
- [phpMyAdmin](#phpmyadmin)
- [phpPgAdmin](#phppgadmin)
- [PostgreSQL](#postgresql)
- [Python](#python)
- [Ruby](#ruby)
- [SVN](#svn)
- [Webgrind](#webgrind)
- [WebSVN](#websvn)
- [XDebugClient](#xdebugclient)
- [Yarn](#yarn)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Adminer

Available as a single PHP file.<br />
[Login server enhanced](https://github.com/crazy-max/login-servers-enhanced) plugin and [Adminer theme by Hever](https://raw.githubusercontent.com/vrana/adminer/master/designs/hever/adminer.css) have been integrated.

* https://github.com/vrana/adminer/releases
* https://github.com/vrana/adminer/blob/master/plugins/plugin.php

## Apache

No rebuild required. Available as archive artefact (zip).

* http://www.apachehaus.com/cgi-bin/download.plx

## Composer

No rebuild required. Available as a single PHAR file.

* https://getcomposer.org/

## ConsoleZ

ConsoleZ with extra dependencies.<br />
See `deps.properties` file on the module repository.

#### ConsoleZ

No rebuild required. Available as archive artefact (zip).

* https://github.com/cbucher/console/releases

#### Clink

No rebuild required. Available as archive artefact (zip).

* https://github.com/mridgers/clink

#### GnuWin32 CoreUtils

No rebuild required. Available as archive artefact for Binaries and Dependencies (zip).

* http://gnuwin32.sourceforge.net/packages/coreutils.htm

## Filezilla Server

Rebuild required, only available as setup executable.<br />
Extracted using 7zip and rebuild without unecessary files (sources, readme).

* http://sourceforge.net/projects/filezilla/files/FileZilla%20Server/
* http://mirror.ufs.ac.za/filezilla/FileZilla%20Server/

## Ghostscript

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://www.ghostscript.com/download/gsdnld.html
* https://github.com/ArtifexSoftware/ghostpdl-downloads/releases

## Git

No rebuild required. Available as portable exe (.exe).

* https://github.com/git-for-windows/git/releases

## Gitlist

No rebuild required. Available as archive artefact (tar.gz).
Requires updating config.ini to point to latest git module
![image](https://user-images.githubusercontent.com/1850089/178372310-8c6b4ed5-0f49-4161-9ebb-90750b71f04b.png)

* http://gitlist.org/

## MailHog

No rebuild required. Available as a single EXE file.

* https://github.com/mailhog/MailHog/releases

## MariaDB

No rebuild required. Available as archive artefact (zip).

* https://downloads.mariadb.org/mariadb/+releases/

## Memcached

No rebuild required. Available as archive artefact (zip).
<b> Windows dll's seem to be no longer being made.</b>

* https://memcached.org/
* https://github.com/memcached/memcached

## MySQL

No rebuild required. Available as archive artefact (zip).

* https://dev.mysql.com/downloads/mysql/

## ngrok

No rebuild required. Available as a single EXE file.

* https://ngrok.com/download

## Node.js

No rebuild required. Available as msi or 7z artefact.

* https://nodejs.org/dist/

## Perl

No rebuild required. Available as archive artefact (zip).

* http://strawberryperl.com/releases.html

## PHP

No rebuild required. Available as archive artefact (zip).

* [php](https://windows.php.net/download)
* [memcache](https://github.com/nono303/PHP-memcache-dll/tags)
* [xdebug](https://xdebug.org/download)
* [imagick](https://windows.php.net/downloads/pecl/deps/)
* [pear](https://pear.php.net/package/pearweb_phars/download/)
<h6><b>Pear requires extracting and using the "install-pear-nozlib.phar"</b></h6> 
<h6>*all of these are required when updating php.</h6>


## phpMemAdmin

No rebuild required. Available as archive artefact (zip).<br />
Taken from sources on Github and version tagged as Travis build number.

* https://github.com/clickalicious/phpMemAdmin/releases

## phpMyAdmin

No rebuild required. Available as archive artefact (zip).

* https://www.phpmyadmin.net/downloads/

## phpPgAdmin

No rebuild required. Available as archive artefact (zip).

* https://github.com/phppgadmin/phppgadmin/releases

Some are available through forked repositories :

* Tomicapo: [phppgadmin-d32e737a0de724ab954a996d5bada363c863770f](https://github.com/Tomicapo/phppgadmin/tree/d32e737a0de724ab954a996d5bada363c863770f)

## PostgreSQL

No rebuild required. Available as archive artefact (zip).

* https://www.enterprisedb.com/products-services-training/pgbindownload

## Python

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* https://winpython.github.io/
* http://www.lfd.uci.edu/~gohlke/pythonlibs/#pyqt4

## Ruby

Rebuild required, only available as setup executable.<br />
Extracted using 7zip.

* http://rubyinstaller.org
* https://rubygems.org

## SVN

Rebuild required, only available as setup executable.<br />
Installed on a computer by selecting SVNSERVE component and rebuilded.

* http://www.collab.net/downloads/subversion

## Webgrind

No rebuild required. Available as archive artefact (zip).

* https://github.com/jokkedk/webgrind/releases

## WebSVN

No rebuild required. Available as archive artefact (zip).

* http://www.websvn.info/download/

## XDebugClient

No rebuild required. Available as archive artefact (zip).

* https://code.google.com/archive/p/xdebugclient/

## Yarn

No rebuild required. Available as msi artefact.

* https://yarnpkg.com/en/docs/install/
