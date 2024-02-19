# Ignite to FireDroid #

<p align="center">
  <img src="https://i.imgur.com/IinnO2x.png"/>
</p>

### Based on Android Open Source Project 

"FireDroid" a Pixel style rom that integrates useful features from known custom ROMs. "Our goal is to deliver a seamless, immersive, and tailor-made experience, ensuring your essential customizations resonate with you, the community, and every individual."

# Build guide

Prior to building, you will need basic knowledge of [Git](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet).

### Requirements

- Around 600G disk space.
- A computer with at least 64GB RAM running Linux (recommended) or MacOS.
- Build environment [setup](https://github.com/akhilnarang/scripts).

### Visit these important repositories:

- [Devices](https://github.com/FireDroid-Devices)
- [Changelogs](https://github.com/FireDroid-Devices/Changelogs)


# FireDroid Project #

### Repo Init ###

```bash

 repo init -u https://github.com/FireDroid-AOSP/manifest -b 14 --git-lfs
```

### Repo Sync ###

```bash

 repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -j$(nproc --all)
```

### Compilation Help

To get help with build errors, please visit [**Android Building Help**](https://t.me/AndroidBuildingHelp).


# For Apply Maintainership

### Requirements
You don't need a lot of skills to be a device maintainer. You only need to have:
- enough git skills to properly handle your device specific repos, and
- the ability to read logs, so you can know any device related issues and fix them.

- [Contact](https://t.me/i_RONAN)

### Follow Officials

- [Telegram Channel](https://t.me/firedroid_official)
