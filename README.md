# Device List

## `Mi8937` (MSM8917 / MSM8937 / MSM8940)
- Redmi 3S / 3X (`land`)
- Redmi 4 Standard (`prada`)
- Redmi 4A (`rolex`)
- Redmi 4X (`santoni`)
- Redmi 5A (`riva`)
- Redmi Note 5A / Y1 Lite (`ugglite`)
- Redmi Note 5A / Y1 Prime (`ugg`)

## `Mi439` (SDM439)
- Xiaomi Redmi 7A (`pine`)
- Xiaomi Redmi 8 (`olive`)
- Xiaomi Redmi 8A (`olivelite`)
- Xiaomi Redmi 8A Dual (`olivewood`)

## `Tiare` - Redmi Go (MSM8917)

## `oxygen` - Mi MAX 2 (MSM8953)

## `vince` - Redmi 5 Plus (MSM8953)

## `uter` - Xiaomi UTER (MSM8953)

## `onc` - Xiaomi Xiaomi Redmi Y3 / Xiaomi Redmi 7 (SDM632)

## `msm8937` - Qualcomm MSM8937 (MSM8937)

# Notes
- If you're going to build ROM which is supported here, Put the corresponding manifest file in `.repo/local_manifests`, re-run `repo sync`, and apply all the patches that's given in this repo.
- If you're going to build ROM which we doesn't support, Make sure to use R HALs and apply all [our commits](https://github.com/Mi-Thorium/android_hardware_qcom_audio/commits/lineage-19.1-caf-msm8953) in Audio HAL.

- Credit:
MiThorium: 0xCafebabe and all other contributors for device trees, kernel sources, common efforts, etc
Gapps: PixysOS team for the vendor_gapps package, cloned to vendor/gms
LineageOS: I have used lineageOS 20 as the base, so thanks a lot to the cyanogenMOD, lineageOS team and contibutors!
ROM-Builders: I did have to move my FlairOS manifests and more to local_manifests just to comply with their small list of ROM building targets but thanks a lot for giving a good platform for allowing learners to build ROMs without any cost
