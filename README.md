# Aodroid 7.1

repo init -u git://github.com/wangshe/platform_manifest.git -b android-7.1

repo sync

source build/envsetup.sh

lunch aosp_thea-userdebug

make -j4 otapackage
