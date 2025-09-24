# LineageOS 22.2 Custom Kernel - SukiSU Ultra for the Sony Xperia 1 V PDX234

Custom kernel for **LineageOS 22.2** on Sony Xperia 1 V devices with SM8550 SoC (PDX234), featuring SukiSU Ultra root solution and advanced hiding capabilities.

## Requirements

- **ROM**: LineageOS 22.2 (Android 15)
- **Device**: Sony Xperia 1 V with SM8550 SoC (PDX234)
- **Recovery**: TWRP

## Features

- **SukiSU Ultra** - Advanced root solution with enhanced hiding
- **SUSFS v1.5.9** - Sophisticated filesystem hiding (ඞ)
- **Manual Syscall Hooks** - Better detection evasion
- **Magic Mount Support** - Systemless modifications
- **LZ4 1.10.0** - Upgraded compression algorithm
- **LZ4KD & ONEPLUS_LZ4K** - Advanced ZRAM optimizations
- **KPM Support** - Kernel Patch Module functionality
- **BBR TCP** - Optimized network congestion control
- **KALLSYMS** - Enhanced kernel debugging support
- **LineageOS Detection Bypass** - Hide custom ROM detection
- **JIT Zygote Cache Hiding** - Advanced process hiding

## Installation

1. Ensure you're running **LineageOS 22.2**
2. Download the latest release from [Releases](../../releases)
3. Boot into custom recovery (TWRP)
4. Flash the AnyKernel3 zip
5. Install the SukiSU Manager APK
6. Reboot

⚠️ **Warning**: Use [Horizon Kernel Flasher](https://github.com/libxzr/HorizonKernelFlasher) only when flashing on the fly.

## Build Variants

- **Stable Branch** (`susfs-main`) - Tested and stable
- **Dev Branch** (`susfs-test`) - Latest features, may be unstable

## Build Options

- **SUSFS** - Enable/disable filesystem hiding
- **KPM** - Enable/disable Kernel Patch Module
- **ZRAM** - Enable/disable LZ4KD optimizations

## Credits, Acknowledgments & Thanks

A post from someone called 'DarkEnd91' on XDA which made me
decide to take on this project.

This project wouldn't be possible without the amazing work from:

### Core Contributors
- **[tiann](https://github.com/tiann)** - Original KernelSU creator
- **[ShirkNeko](https://github.com/ShirkNeko)** - SukiSU Ultra development and patches
- **[simonpunk](https://gitlab.com/simonpunk)** - SUSFS development
- **[zzh20188](https://github.com/zzh20188)** - LZ4 1.10.0 upgrade patches and improvements
- **[Tools-cx-app](https://github.com/Tools-cx-app)** - Kernel patches repository
- **[WildPlusKernel](https://github.com/WildPlusKernel)** - AnyKernel3 GKI branch

### Special Thanks
- **LineageOS Team** - For the LineageOS 22.2 kernel source
- **Sony Open Devices Project** - For device support
- **[sidex15](https://github.com/sidex15)** - SUSFS module development
- **[libxzr](https://github.com/libxzr)** - Horizon Kernel Flasher
- **[osm0sis](https://github.com/osm0sis)** - Original AnyKernel3

### Community
- All testers and users who provided feedback
- The KernelSU community for continuous support
- Android kernel development community

## Resources

- **Manager**: [SukiSU-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra)
- **Modules**: [ksu_module_susfs](https://github.com/sidex15/ksu_module_susfs)
- **Support**: Open an issue in this repository

## License

This kernel is based on the Linux kernel and inherits its GPLv2 license. All modifications are also released under GPLv2.

## Disclaimer

This kernel is provided as-is without any warranty. Use at your own risk. Always backup your data before flashing custom kernels.

---

**Note**: In SUS SU Mode 2, it may show as disabled or incompatible because non-kprobe hooks are used during compilation, which are no longer needed.
