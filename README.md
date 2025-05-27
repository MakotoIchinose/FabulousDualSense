# Fabulous DualSense

This fork is continuation of the upstream Fabulous DualSense repository. However, the changes will be only maintenance focused (i.e. making sure it compile with newer Unreal Engine versions), and currently have no intentions for new features.

This plugin is mainly intended to be an interim solution with DualSense inputs without requiring XInput remappers like Steam Input or DualSenseX, official Sony libraries for console development, or paid plugins. It is not recommended to use in final shipping builds, especially if you have access to official Sony libraries to get **Windows DualShock** plugin working.

## Description

Input device plugin for the **DualSense** controller on **Windows** for **Unreal Engine**.

This plugin includes generic gamepad, touchpad, and gyroscope functionality, as well as partial support for the [Device Properties](https://dev.epicgames.com/documentation/en-us/unreal-engine/device-properties-in-unreal-engine) feature (supported device properties are **Device Color**, **Trigger Feedback**, and **Trigger Resistance**).

**Linux** support is not guaranteed.

## Quick Start

1. Clone the repository to your project's `Plugins` folder.
2. Recompile your project.

## Credits

- [DualSense Windows API](https://github.com/mattdevv/DualSense-Windows) by Matthew Hall

## License & Contribution

Fabulous DualSense is licensed under the MIT License, see [LICENSE.md](LICENSE.md) for more information. Other developers are encouraged to fork the repository, open issues & pull requests to help the development.
