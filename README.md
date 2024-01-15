# TWRP Device Tree for Xiaomi Redmi 12

The Xiaomi Redmi 12 (codenamed _"fire"_) is a mid-range smartphone from Xiaomi.

It was announced and released in June 2023.

## Device specifications

| Feature                        | Specification                                                                             |
| -----------------------------: | :---------------------------------------------------------------------------------------- |
| Chipset                        | Mediatek MT6769H Helio G88                                                        |
| CPU                            | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55) |
| GPU                            | Mali-G52 MC2                                                                      |
| Memory                         | 4GB / 6GB / 8GB RAM (LPDDR4X)                                                                  |
| Shipped OS                     | Android 13, MIUI 14                                                                   |
| Storage                        | 128GB / 256GB (eMMC 5.1)                                                                   |
| SIM                            | Hybrid Dual SIM (Nano-SIM, dual stand-by)                                                 |
| MicroSD                        | Up to 1TB                                                                                 |
| Battery                        | 5000mAh Li-Po (non-removable), 18W fast charge                                           |
| Dimensions                     | 168.6 x 76.3 x 8.2 mm (6.64 x 3.00 x 0.32 in)                                             |
| Display                        | 6.79", 1080 x 2460 pixels, IPS LCD, 90Hz (~396 ppi density)              |
| Rear Camera 1                  | 50 MP, f/1.8, (wide), PDAF                                       |
| Rear Camera 2                  | 8 MP, f/2.2, 120˚ (ultrawide)                                                    |
| Rear Camera 3                  | 2 MP, f/2.4, (macro)                                                                      |
| Front Camera                   | 8 MP, f/2.1                                                  |
| Fingerprint                    | (side-mounted)                                                    |
| Sensors                        | accelerometer, compass                          |


## Device picture

![xiaomi-redmi-12-1](https://github.com/AntarticShaurant/android_device_xiaomi_fire/assets/109678650/bd593af4-92d4-4d5a-872d-e21bbb699a89)


## WARNING

This device tree hasn't been tested yet, use it at your own risk.
That said, feel free to test it, and report bugs, i'll try my best to solve them.

## How to build

1. Set up the build environment following the instructions [here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp/blob/twrp-12.1/README.md#getting-started)

2. In the root folder of the fetched repo, clone the device tree:

```bash
git clone https://github.com/AntarticShaurant/android_device_xiaomi_fire.git device/xiaomi/fire
```

3. To build:

```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp-fire-eng
mka bootimage
```
