![LegionOS](https://i.imgur.com/6qCMrc2.png[/img])

---------------------------------------------------------------------------------------
 Getting Started:
 ==============

To get started with manifest/legionos, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init --depth=1 -u https://github.com/masemoel/minimal_manifest_legion-r.git -b 11

```

Then to sync up:

```
repo sync --current-branch --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$( nproc --all ) && repo sync --current-branch --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$( nproc --all ) && . build/envsetup.sh && make clobber
```
---------------------------------------------------------------------------------------
 Compilation of  LegionOS:
 ==================

From root directory of project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch legion_<device_codename>-buildtype
$ make legion
```
---------------------------------------------------------------------------------------
 Maintainership:
 ================

 Apply for official maintainership [**Here**](https://github.com/Project-LegionOS/Docs)

---------------------------------------------------------------------------------------
 TeamLegionOS
 ===============

 * [**Rajkale99**](https://t.me/rajkale99) - Founder & Lead Developer
 * [**Lucas**](https://t.me/pintos) - Device Manager
 * [**Anon Hacker**](https://t.me/AnonymousHacker_47) - Chief Designer
 * [**Immanuel Raj**](https://t.me/Immanuel_Raj) - Website maintainer & cherry-picker
 
---------------------------------------------------------------------------------------
 Credits:
 =======

 * [**LineageOS**](https://github.com/LineageOS)
 * [**Xtended**](https://github.com/Project-Xtended)
 * [**Colt**](https://github.com/Colt-Enigma)
 * [**ROS**](https://github.com/RevengeOS)
 * [**ManyMore from where cherry-picked from**](https://github.com)

---------------------------------------------------------------------------------------

Thread template for Xda refer [**HERE**](https://github.com/Project-LegionOS/xda_template/blob/10/template.txt)
