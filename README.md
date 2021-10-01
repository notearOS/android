# notearOS

## Requirements

I recommend using Ubuntu 20.04 to build notearOS. Refer to [LineageOS build instructions](https://wiki.lineageos.org/devices/bacon/build) on how to setup your environment.

## Instructions

```bash
mkdir notearOS
cd notearOS

repo init -u https://github.com/notearOS/android.git -b eleven

repo sync -c --no-clone-bundle --current-branch --no-tags -j8
```
