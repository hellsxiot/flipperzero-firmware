# Flipper Zero Firmware (Fork)

This is a fork of [flipperdevices/flipperzero-firmware](https://github.com/flipperdevices/flipperzero-firmware) with additional features and fixes.

## What is Flipper Zero?

Flipper Zero is a portable multi-tool for pentesters and geeks in a toy-like body. It can interact with digital systems in real life and grow while you use it. Flipper Zero is fully open-source and customizable, so you can extend it in whatever way you like.

## Building

### Prerequisites

- [Git](https://git-scm.com/)
- [Python 3](https://www.python.org/downloads/) (3.8+)
- [ARM GCC Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm)

### Clone the repository

```sh
git clone --recursive https://github.com/your-username/flipperzero-firmware.git
cd flipperzero-firmware
```

### Build

```sh
./fbt
```

To build and flash over USB:

```sh
./fbt flash_usb_full
```

## Differences from upstream

- Additional bugfixes
- Community-requested features
- Performance improvements

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate and follow the existing code style (enforced via `.clang-format`).

## License

[GNU General Public License v3.0](LICENSE)
