Marble KP
============

The following instructions will allow you to sync and build the kernel for Solana Saga (ingot)

# Sync

```
repo init -u https://github.com/pc-marble/kp.git -b kp
```

# Build
```
EXT_MODULES="private/sm8450-modules/qcom/opensource/mmrm-driver private/sm8450-modules/qcom/opensource/datarmnet/core private/sm8450-modules/qcom/opensource/datarmnet-ext/offload private/sm8450-modules/qcom/opensource/datarmnet-ext/shs private/sm8450-modules/qcom/opensource/camera-kernel/ private/sm8450-modules/qcom/opensource/video-driver/ private/sm8450-modules/qcom/opensource/wlan/qcacld-3.0/ private/sm8450-modules/qcom/opensource/audio-kernel/ private/sm8450-modules/qcom/opensource/display-drivers/ private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/audio private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/camera private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/cvp private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/display private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/eva private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/mmrm private/msm-5.10/arch/arm64/boot/dts/vendor/qcom/video private/sm8450-modules/qcom/opensource/datarmnet-ext/aps/ private/sm8450-modules/qcom/opensource/datarmnet-ext/perf private/sm8450-modules/qcom/opensource/datarmnet-ext/perf_tether private/sm8450-modules/qcom/opensource/datarmnet-ext/sch private/sm8450-modules/qcom/opensource/datarmnet-ext/wlan private/sm8450-modules/qcom/opensource/dataipa/drivers/platform/msm private/sm8450-modules/qcom/opensource/cvp-kernel private/sm8450-modules/qcom/opensource/eva-kernel" KERNEL_DIR=private/msm-5.10 BUILD_CONFIG=private/msm-5.10/build.config.msm.marble VARIANT=gki build/build.sh
```
