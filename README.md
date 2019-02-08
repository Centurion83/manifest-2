-----------------------------------------------------------------------------

<p align="center">
 <img src="https://github.com/SuperiorOS/manifest/blob/pie/superior.png" > 
</p>

-----------------------------------------------------------------------------
Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DotOS**](https://github.com/DotOS)
 * [**PixelExperience**](https://github.com/PixelExperience)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**AospExtended**](https://github.com/AospExtended)
 * [**Syberia OS**](https://github.com/syberia-project)
 * [**Nitrogen OS**](https://github.com/nitrogen-project)
 * [**Pixys OS**](https://github.com/PixysOS)
 * [**ArrowOS**](https://github.com/ArrowOS)
 * [**MSM-Xtended**](https://github.com/Project-Xtended)
 * [**HavocOS**](https://github.com/Havoc-OS)
 * [**BootleggersROM**](https://github.com/BootleggersROM)
 * [**ABC**](https://github.com/ezio84?tab=repositories)

-----------------------------------------------------------------------------

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
    repo init -u git://github.com/SuperiorOS/manifest.git -b pie
```

Then to sync up:-
================

```bash
    repo sync --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken --force-sync -j8
```

Start the build:-
=================

```bash
  . build/envsetup.sh
  lunch superior_<devicecodename>-userdebug
  mka bacon -jx
```
-----------------------------------------------------------------------------

Some Links:-
============
* [**Google Plus**](https://plus.google.com/communities/109206747517820828242)
* [**Telegram Public Chat**](https://t.me/superioros)
* [**Telegram Channel**](https://t.me/superior_os)

----------------------------------------------------------------------------

Download Stats
==============

[![Download Superior](https://img.shields.io/sourceforge/dd/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download) 

[![Download Superior](https://img.shields.io/sourceforge/dw/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download) 

[![Download Superior](https://img.shields.io/sourceforge/dm/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download) 

[![Download Superior](https://img.shields.io/sourceforge/dt/superioros.svg)](https://sourceforge.net/projects/superioros/files/latest/download) 
---------------------------------------------------------------------------------
