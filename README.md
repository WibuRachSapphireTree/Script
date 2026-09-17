## Clone Device Trees

```bash
# Clone Device Trees for Sapphire
echo "Cloning Device Trees for Sapphire..."

rm -rf device/xiaomi/sapphire-kernel
git clone --depth 1 -b lineage-23.2 https://github.com/WibuRachSapphireTree/device_xiaomi_sapphire-kernel device/xiaomi/sapphire-kernel

rm -rf device/xiaomi/sepolicy
git clone --depth 1 -b 16 https://github.com/WibuRachSapphireTree/device_xiaomi_sepolicy device/xiaomi/sepolicy

rm -rf device/xiaomi/sapphire
git clone --depth 1 -b lineage-23.2 https://github.com/WibuRachSapphireTree/device_xiaomi_sapphire device/xiaomi/sapphire

rm -rf vendor/xiaomi/sapphire
git clone --depth 1 -b lineage-23.2 https://github.com/WibuRachSapphireTree/vendor_xiaomi_sapphire vendor/xiaomi/sapphire

rm -rf hardware/xiaomi
git clone --depth 1 -b lineage-23.2 https://github.com/WibuRachSapphireTree/android_hardware_xiaomi hardware/xiaomi

rm -rf hardware/dolby
git clone --depth 1 https://github.com/WibuRachSapphireTree/hardware_dolby hardware/dolby

echo "============================"
echo "Device Trees cloned successfully"
echo "============================"
```

## Clone HALs for SM6225

```bash
# Clone HALs for SM6225
echo "Cloning HALs for SM6225..."

rm -rf hardware/qcom-caf/common
git clone --depth 1 -b lineage-23.2 https://github.com/sapphire-sm6225/android_hardware_qcom-caf_common.git hardware/qcom-caf/common

rm -rf hardware/qcom-caf/sm6225/audio/agm
git clone --depth 1 -b lineage-22.2-caf-sm6225 https://github.com/sapphire-sm6225/vendor_qcom_opensource_agm.git hardware/qcom-caf/sm6225/audio/agm

rm -rf hardware/qcom-caf/sm6225/audio/pal
git clone --depth 1 -b lineage-22.0-caf-sm6225 https://github.com/sapphire-sm6225/vendor_qcom_opensource_arpal-lx.git hardware/qcom-caf/sm6225/audio/pal

rm -rf hardware/qcom-caf/sm6225/data-ipa-cfg-mgr
git clone --depth 1 -b lineage-22.0-caf-sm6225 https://github.com/sapphire-sm6225/vendor_qcom_opensource_data-ipa-cfg-mgr.git hardware/qcom-caf/sm6225/data-ipa-cfg-mgr

rm -rf hardware/qcom-caf/sm6225/dataipa
git clone --depth 1 -b lineage-22.0-caf-sm6225 https://github.com/sapphire-sm6225/vendor_qcom_opensource_dataipa.git hardware/qcom-caf/sm6225/dataipa

rm -rf hardware/qcom-caf/sm6225/display
git clone --depth 1 -b lineage-22.0-caf-sm6225 https://github.com/sapphire-sm6225/hardware_qcom_display.git hardware/qcom-caf/sm6225/display

rm -rf hardware/qcom-caf/sm6225/media
git clone --depth 1 -b lineage-22.0-caf-sm6225 https://github.com/sapphire-sm6225/hardware_qcom_media.git hardware/qcom-caf/sm6225/media

rm -rf hardware/qcom-caf/sm6225/audio/primary-hal
git clone --depth 1 -b lineage-22.0-caf-sm6225 https://github.com/sapphire-sm6225/hardware_qcom_audio.git hardware/qcom-caf/sm6225/audio/primary-hal

rm -rf device/qcom/sepolicy_vndr/sm6225
git clone --depth 1 -b lineage-23.0-caf-sm6225 https://github.com/sapphire-sm6225/device_qcom_sepolicy_vndr.git device/qcom/sepolicy_vndr/sm6225

echo "============================"
echo "HALs cloned successfully"
echo "============================"
```

Clone Full
```bash
# Clone Device Trees for Sapphire (Full history)
echo "Cloning Device Trees for Sapphire..."

rm -rf device/xiaomi/sapphire-kernel
git clone -b lineage-23.2 https://github.com/WibuRachSapphireTree/device_xiaomi_sapphire-kernel device/xiaomi/sapphire-kernel

rm -rf device/xiaomi/sepolicy
git clone -b 16 https://github.com/WibuRachSapphireTree/device_xiaomi_sepolicy device/xiaomi/sepolicy

rm -rf device/xiaomi/sapphire
git clone -b lineage-23.2 https://github.com/WibuRachSapphireTree/device_xiaomi_sapphire device/xiaomi/sapphire

rm -rf vendor/xiaomi/sapphire
git clone -b lineage-23.2 https://github.com/WibuRachSapphireTree/vendor_xiaomi_sapphire vendor/xiaomi/sapphire

rm -rf hardware/xiaomi
git clone -b lineage-23.2 https://github.com/WibuRachSapphireTree/android_hardware_xiaomi hardware/xiaomi

rm -rf hardware/dolby
git clone https://github.com/WibuRachSapphireTree/hardware_dolby hardware/dolby

echo "============================"
echo "Device Trees cloned successfully"
echo "============================"
```
