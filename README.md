# firmware-repo-manifest

This is the Snapp Automotive repo manifest to check out the AOSP based Snapp Automotive image.

To checkout the complete tree you should follow the [AOSP instructions](https://source.android.com/setup/develop), but, where they say 
`repo init -u https://android.googlesource.com/platform/manifest -b master` you should, instead, run;

```
$ repo init -u git@github.com:snappautomotive/firmware-repo-manifest.git -b sa-main
```

When you select a lunch target you should choose `snapp_car_x86-userdebug` (or `-eng` if you want to do low level debugging).
