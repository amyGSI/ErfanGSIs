# ErfanGSIs Tool - amyGSI Edition

This repository is a fork of a fork of the ErfanGSIs Tool for private use, you are free to create your fork and make your changes (at least give the credits to all contributors of the ErfanGSIs Tool project).

See also the [ErfanGSIs-Builder](https://github.com/amyGSI/ErfanGSIs-Builder) repository where you can see GSIs being made with GitHub Actions.

You can find GSIs made with this tool on the channel [@amyGSI](https://t.me/amyGSI) on Telegram.

### Download tools

```
git clone --recurse-submodules https://github.com/amyGSI/ErfanGSIs.git
cd ErfanGSIs
```

### Setting up requirements

```
bash setup.sh
```

## Usage

```
./url2GSI.sh <Firmware link> <Firmware type> [Other args]
[--help|-h|-?] [--ab|-b] [--aonly|-a] [--mounted|-m] [--cleanup|-c]
        Firmware link: Firmware download link or local path
        Firmware type: Firmware mode
        --ab: Build only AB
        --aonly: Build only A-Only
        --cleanup: Cleanup downloaded firmware
        --help: To show this info
```

### Supported firmware types

```
Supported types on Android 9:
Nubia, Moto, OneUI, MIUI, OxygenOS, ZenUI, Generic, Flyme, Pixel, ColorOS, ZUI, Xperia, RazerUI, VOS, RogUI

Supported types on Android 10:
MIUI, OxygenOS, Generic, Pixel, AncientOS, EvolutionX, JoyUI, Moto, PixelExperience, ZenUI, ZUI, Flyme, ColorOS, VOS, OneUI

Supported types on Android 11:
Generic, Pixel
```
### Credits

Hitsuki for his edits to the tool
Erfan for the original tool
