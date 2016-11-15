# Android Manifest

```
$ repo init -u https://github.com/rosterloh/android_manifest.git -b apq8096
```

-g : default,-darwin,-device,-x86,-mips

## Sync options

 * -c, --current-branch **fetch only current branch from server**
 * -f, --force-broken **continue sync even if a project fails to sync**
 * -d, --detach **detach projects back to manifest revision**

## Building

```
$ source build/envsetup.sh
$ lunch
$ make -j8
```
