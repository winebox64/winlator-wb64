<p align="center">
	<img src="winlatorwb64" width="376" height="128" alt="Winlator WB64" />  
</p>

# Winlator WB64

Winlator WB64 is an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64.

----

# Installation PRoot - Glibc

1. Download and install the APK from GitHub Releases [![winlator winebox64 apk](https://img.shields.io/badge/%20Download%20-wb64?style=for-the-badge-plastic&logo=Androids&logoColor=green&logoSize=14&label=%20&labelColor=golden&color=66BA32)](https://github.com/winebox64/winlator/releases)
2. Launch the app and wait for the installation process to finish

----

# System Requirements WB64 version:
- __OS (Operating System):__ Android 9.0 or later
- __Processor/CPU (Central Processing Unit):__ Qualcomm Snapdragon 460 or higher
- __GPU (Graphics Processing Unit):__ Adreno 610 or higher 
- __Graphics API:__ Vulkan 1.1 or higher
- __Internal Storage/ROM:__ At least 2GB of free space
- __RAM (Random Access Memory):__ At least 1GB of free RAM available, depending on the game requirments
- __Root Access:__ Not required
- __Gamepad:__ Optional (xinput/xbox recommended)

__Results can vary based on the device used, environmental conditions, and other factors, such as simultaneous processing, and different processor capabilities.__

----

# Useful Tips

- If you are experiencing performance issues, try changing the Box64 preset to `Performance` in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing `Wine Mono` found in Start Menu -> System Tools -> Installers.
- If some older games don't open, try adding the environment variable `MESA_EXTENSION_MAX_YEAR=2003` in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- To display low resolution games correctly, try to enabling the `Force Fullscreen` option in the shortcut settings.
- To improve stability in games that uses Unity Engine, try changing the Box64 preset to `Stability` or in the shortcut settings add the exec argument `-force-gfx-direct`.

----

## Vortek Driver (Experimental)

The Vortek driver is for processors that are incompatible with the Turnip (Adreno) driver.

[![Qualcomm](https://img.shields.io/badge/Snapdragon%208%20Elite-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%207s%20Gen%203-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%207%20Gen%203-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%207s%20Gen%202-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%206%20Gen%203-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%206%20Gen%201-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%20860-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

[![Qualcomm](https://img.shields.io/badge/Snapdragon%20735-grey?style=plastic&logo=snapdragon&logoColor=red)](https://github.com/winebox64/winlator)

----

# Information

This project has been in constant development since version 1.0, the current app source code is up to version 7.1, I do not update this repository frequently precisely to avoid unofficial releases before the official releases of Winlator.

----

# Credits and Third-party apps
- GLIBC Patches by [Termux Pacman](https://github.com/termux-pacman/glibc-packages)
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- Mesa (Turnip/Zink/VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- PRoot ([proot-me.github.io](https://proot-me.github.io))

Many thanks to [ptitSeb](https://github.com/ptitSeb), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/), [Max Ivan](https://github.com/Maxython), [Twaik Yont](https://github.com/twaik), [alexvorxx](https://github.com/alexvorxx) and others.<br>
Thank you to all the people who believe in this project.
