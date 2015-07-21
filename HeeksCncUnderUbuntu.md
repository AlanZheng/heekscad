# Introduction #

There are 3 ways to use HeeksCNC suite:
  * The easiest is to use PPA to install directly Ubuntu packages
  * If you want to build it locally, it recommended to use [Debian packaging way](BuildDebianPackages.md)
  * Or you can build it using CMake, [the regular way](BuildHeeksCncUnderLinux.md)

# Use PPA (Personal Package Archives) #

HeeksCNC and related tools (HeeksCAD, libarea, OpenCAMLib) are daily packaged in [heekscnc-devel PPA](https://launchpad.net/~neomilium/+archive/heekscnc-devel).

Note: this PPA provides development versions of HeeksCNC, HeeksCAD, libarea and OpenCAMLib.

Supported versions: Lucid (10.04 LTS), Precise (12.04 LTS), Saucy (13.10), Trusty (14.04 LTS), Utopic (14.10).

Add [heekscnc-devel PPA](https://launchpad.net/~neomilium/+archive/heekscnc-devel) to your repositories list:
```
sudo add-apt-repository ppa:neomilium/heekscnc-devel
```

Update your packages list:
```
sudo apt-get update
```

Install HeeksCNC:
```
sudo apt-get install heekscnc
```

# Build it the Debian way #

This method allow you to build all Debian packages related to HeeksCNC.

Instructions are available on a [dedicated wiki page](BuildDebianPackages.md)

# Build it the standard way #

This method allow you to build HeeksCNC and its dependencies using CMake.

Instructions are available on a [dedicated wiki page](BuildHeeksCncUnderLinux.md) and in _README.Unix_ file in sources root directory.