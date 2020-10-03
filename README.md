# RevengeOS #

<img src="https://raw.githubusercontent.com/RevengeOS/android_manifest/r10.0/RevengeOs-logo.jpg"> 

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------

Warning:
==============

The ROM is still in **alpha** stage. Reach us on [Telegram](https://t.me/itsrevengeos) in order to report any compilation issue / bug.

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/OGHyperion/android_manifest -b r11.0
```
Then to sync up:
================

```bash
repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
```

Finally to build:
====================

From root directory of Project, perform following commands in terminal


```bash
source build/envsetup.sh
lunch revengeos_<devicecodename>-user
make bacon
```
-----------------------------------------------------------------------------

## Report build issues
- You can reach us via [Telegram](https://t.me/itsrevengeos)

## Maintain Officially
- If you're building **RevengeOS** for an unofficial device and would like to make it official, Check out the link below.  
- [Click here for more info](https://forms.gle/aW2jQNRGFzUGgWED7)

Some Links:-
============
* [**Website**](https://www.revengeos.com)
* [**Telegram Public Chat**](https://t.me/itsrevengeos)
* [**Telegram Channel**](https://t.me/RevengeOSNews)
* [**Twitter**](https://twitter.com/itsrevengeos)

