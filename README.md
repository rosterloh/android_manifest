# Android Manifest for [Dragonboard 410c](http://www.96boards.org/products/ce/dragonboard410c/)

Current tag is [LA.BR.1.2.7-02810-8x16.0](https://source.codeaurora.org/quic/la/platform/manifest/tag/?h=LA.BR.1.2.7-02810-8x16.0)

```
$ repo init -u https://github.com/rosterloh/android_manifest.git -b dragonboard
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
