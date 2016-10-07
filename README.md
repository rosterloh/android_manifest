# Android Manifest

```
$ repo init -u https://android.googlesource.com/platform/manifest -b android-7.0.0_r14
$ cd .repo
$ git clone https://github.com/rosterloh/android_manifest.git -b rpi3 local_manifests
```

-g : default,-darwin,-device,-x86,-mips

## Sync options

 * -c, --current-branch **fetch only current branch from server**
 * -f, --force-broken **continue sync even if a project fails to sync**
 * -d, --detach **detach projects back to manifest revision**

## Building

```
$ source build/envsetup.sh
$ lunch rpi3-eng
$ make -j8
```
