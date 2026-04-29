<div align="center">
  <h1>Boot Animations for custom roms</h1>
</div>


<div align="left">
Implements custom custom bootlogos for Samsung phones (after 2015?) on devices with Magisk/KernelSU as its root solution/method.

These .bin files replace the default bootlogo with themed ones, offering a personalized boot-up experience :3
</div>

<div align="center">
  <h3>All themes are provided as magisk/ksu flashable .zip files. so just install them as a module</h3>

[![Magisk 420+](https://img.shields.io/badge/Magisk-420+-000000?style=flat&logo=magisk&logoColor=lightgreen)](https://github.com/topjohnwu/Magisk)
[![Android 5-16](https://img.shields.io/badge/Android-1%E2%86%9216-000000?style=flat&logo=android&logoColor=white)](https://www.android.com/)

________________________________________________________________

| Theme | Preview | Download |
|-------|---------|----------|
| **HyperOS** | <img src="previews/HyperOS.gif" alt="HyperOS" width="160"> | [download](https://github.com/Boffyz/Boot-animations-on-.zip-format-for_magisk-ksu/releases/download/bootanimation/Rainbow.AOKP.zip) |  |
| *More coming soon!* |  |  |  |
</div>

## Important Distinctions

1. This project targets the **boot animation** that plays after the bootlogo, during the Android system startup.
2. They are not for samsung phones with stock (rooted) oneui as their os

> [!TIP]
> if you're looking for samsung .qmg bootanimations, go to https://github.com/John0n1/SMbootFX

## How It Works

the rom your on reads the bootanimation.zip file, which shows it based on its resolution and frames it was compressed with


## Installation Guide

1. **Download** your chosen boot animation
2. **Open** magisk (ksu).
3. install it as a module (duh).
4. **Reboot** your device.
5. **Enjoy** the new boot animation :3

> [!TIP]
> some bootanimations may not show (and would make your phone get stuck on the bootlogo till booting your phone without a bootanimation), so if they don't, choose another one or convert it to your phone's resolution


## Credits

The .zip files used in this project are made by various creators and devs, and credits goes to their respective owner

## How It Works

the samsung phone you're on reads the up_param.bin file, which shows it based on its resolution (duh)

## Important Notes

- these files are only for android based devices that are made by samsung.
- Use at your own risk—always back up your device before modifying system files.
- inspired by https://github.com/John0n1/SMbootFX

## Troubleshooting

- If the bootlogo doesn't change, ensure you've moved it to the right directory.

## Supported Devices

Most phones devices manufactured after 2015 are supported.

more specifically the ones that does not have adv-env.img inside of its up_param.bin file

Confirmed working on:

* **Galaxy A series:** A13 (A135F)

To confirm support for your specific device, check if yours has support for custom bootlogos

since this is for samsung exynos devices, check if it has this inside of its bootloader:

* `up_param.bin`

If that file is present, your device should be compatible.

## Contributions and Requests

Feel free to open an issue, feature requests, or new theme suggestions.  
Pull requests are welcome for new themes or improvements!

## Credits

The .bin files used in this project are made by me, and the image (that I added to these bootlogos) credits goes to their respective owner

## Notices

- This project is **not** affiliated with, sponsored, or endorsed by Samsung Electronics Co., Ltd., or any other mentioned or themed brands. All trademarks are the property of their respective owners.
- The `.bin` files are only distributed inside as replaceable files in the **Releases** section due to GitHub file size limitations.
- Be cautious when downloading forked versions—especially faulty `bootlogos` from unknown sources, as they may softbrick.


## License

This project is licensed under the [GNU](LICENSE).
