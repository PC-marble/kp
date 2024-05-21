Marble KP
============

The following instructions will allow you to sync and build the kernel for Solana Saga (ingot)

# Sync

```
repo init -u https://github.com/pc-marble/kp.git -b kp
```

# Build
```
EXT_MODULES="private/modules/qcom/opensource/mmrm-driver private/modules/qcom/opensource/datarmnet/core private/modules/qcom/opensource/datarmnet-ext/offload private/modules/qcom/opensource/datarmnet-ext/shs private/modules/qcom/opensource/camera-kernel/ private/modules/qcom/opensource/video-driver/ private/modules/qcom/opensource/wlan/qcacld-3.0/ private/modules/qcom/opensource/audio-kernel/ private/modules/qcom/opensource/display-drivers/ private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/audio private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/camera private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/cvp private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/display private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/eva private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/mmrm private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/video private/modules/qcom/opensource/datarmnet-ext/aps/ private/modules/qcom/opensource/datarmnet-ext/perf private/modules/qcom/opensource/datarmnet-ext/perf_tether private/modules/qcom/opensource/datarmnet-ext/sch private/modules/qcom/opensource/datarmnet-ext/wlan private/modules/qcom/opensource/dataipa/drivers/platform/msm private/modules/qcom/opensource/cvp-kernel private/modules/qcom/opensource/eva-kernel" KERNEL_DIR=private/msm-5.10 BUILD_CONFIG=private/msm-5.10/build.config.msm.marble VARIANT=gki build/build.sh
```
