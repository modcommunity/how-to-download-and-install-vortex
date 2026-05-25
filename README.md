In this guide we will show you how to download and install [Vortex](https://www.nexusmods.com/vortex) on your computer.

[**View Guide On TMC (Recommended Due To Better Formatting)**](https://blog.moddingcommunity.com/how-to-download-install-vortex/)

[Vortex](https://www.nexusmods.com/vortex) is [Nexus Mods](https://www.nexusmods.com/) official **mod manager**, and is the recommended method for managing and installing mods through Nexus Mods when available. It makes it easy to download and install mods, and also provides features such as mod profiles, load order management, and more.

## Table of Contents
- [Requirements](#requirements)
- [Downloading](#downloading)
- [Installing](#installing)
- [Notes](#notes)
    - [Linux](#linux)
- [See Also!](#see-also)

## Requirements
- This guide assumes you have a computer running **Windows 10** or later or Linux.
    - For Linux users, please **follow the guide** and **read the notes** in the [Linux section](#linux) below.
- At least 1 GB of free storage space.

## Downloading
There are two sources you can download the Vortex executable from:

1. The official [Nexus Mods website](https://www.nexusmods.com/vortex) ([direct download](https://nexusmodsapp.nexusmods.com/NexusModsVortexSetup.exe))
2. From releases in the [GitHub repository](https://github.com/Nexus-Mods/Vortex/releases) ([direct download](https://github.com/Nexus-Mods/Vortex/releases/download/v2.0.2/vortex-setup-2.0.2.exe) for `v2.0.2`)

![Vortex Setup Executable](https://github.com/modcommunity/how-to-download-and-install-vortex/raw/main/images/vortex_setup.png)

## Installing
To install the application, simply run the executable file by double-clicking on it (or right-clicking -> **Open**).

The first option will ask you to select the installation location. You can choose the default location or select a different one.

![Vortex Installation Location](https://github.com/modcommunity/how-to-download-and-install-vortex/raw/main/images/vortex_setup-loc.png)

Afterwards, continue through the installation. It should take anywhere from 30 seconds to a few minutes depending on your computer. Once the installation is complete, you can launch Vortex and start using it to manage your mods!

![Vortex Installation Complete](https://github.com/modcommunity/how-to-download-and-install-vortex/raw/main/images/vortex_setup-com.png)

## Notes
### Linux
While there **is support** for running Vortex on Linux, it does require you to perform some additional steps.

[This](https://www.reddit.com/r/linux_gaming/comments/1n1qt7t/guide_to_installing_vortex_mod_manager_on_linux/) guide on Reddit provides a walkthrough along with useful information.

#### Getting Vortex to Run on Linux
In short, you will need to download and install the following applications and frameworks:

- [Heroic Games Launcher](https://heroicgameslauncher.com/)
- [.NET Desktop Runtime 6.0.36](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.36-windows-x64-installer)
    - Just download the executable file, do not run the installer until the next step.

Afterwards, download the Vortex executable (steps detailed above) and perform the following steps:

1. Open HGL and go to **Library** -> **Add Game**.
2. Give a name for the game (e.g. "Vortex").
3. At the bottom, click the **Run Installer First** and then run the Vortex executable you downloaded.
4. Again, click the **Run Installer First** button and run the .NET Desktop Runtime installer you downloaded.
5. After the installation is complete, you will need to click the **Select Executable** button and select the file location of where Vortex was installed.
    * For most users, this will be in: `/home/{USERNAME}/Games/Heroic/Prefixes/default/Vortex Mod Manager/pfx/drive_c/Program Files/Black Tree Gaming Ltd/Vortex/`
6. Click the **Finish** button and that should be it! Now you can launch Vortex, sign into Nexus Mods, and start downloading and installing mods.

**NOTE** - For advanced users, you may select different Wine prefixes and configurations.

#### Adding & Configuring Games
Now that you have Vortex running, you will need to add your games to it. In the guide linked above, the instructions are as follows:

1. Add your games through *HGL* by going to **Library** -> **Add Game**.
2. Click on the **Show Wine** settings button.
3. Change the `WinePrefix` path to point where your new Vortex prefix/installation is located.
    * Common path noted above: `/home/{USERNAME}/Games/Heroic/Prefixes/default/Vortex Mod Manager/pfx/drive_c/Program Files/Black Tree Gaming Ltd/Vortex/`
4. Start Vortex and now you should be able to manage your games through there!

## See Also!
- [Linux Guide on Reddit](https://www.reddit.com/r/linux_gaming/comments/1n1qt7t/guide_to_installing_vortex_mod_manager_on_linux/)
- [Heroic Games Launcher](https://heroicgameslauncher.com/)

## Conclusion
[Vortex](https://www.nexusmods.com/vortex) is a powerful and user-friendly mod manager that can help you easily manage and install mods for games [Nexus Mods](https://www.nexusmods.com/) supports. By following the steps outlined in this guide, you should now have Vortex installed and ready to use on your computer. 

Guides we create are always open to edits and improvements, so if you have any suggestions or notice any issues, feel free to contribute by creating a [pull request](https://github.com/modcommunity/how-to-download-and-install-vortex/pulls) on our GitHub repository!
