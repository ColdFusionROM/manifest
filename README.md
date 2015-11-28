Cold Fusion AOSP ROM

repo init -u https://github.com/ColdFusionROM/manifest.git -b mm6.0

repo sync

source build/envsetup.sh

lunch

make -j16 otapackage
