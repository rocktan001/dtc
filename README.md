### android dtc 

### git://git.kernel.org/pub/scm/utils/dtc/dtc.gi

```
	1:安装默认工具 flex bison
	2:指定交叉编译器 ANDROID_NDK_HOME=/media/disk2/tools/android-ndk-r10e
	3：source generate_standalone_toolchain.sh
	4：make
	5:adb push Y:\github\github-android\dtc\dtc /data/local/tmp
	6:adb shell chmod 777 /data/local/tmp/dtc
	7:adb shell /data/local/tmp/dtc -I fs /proc/device-tree
```