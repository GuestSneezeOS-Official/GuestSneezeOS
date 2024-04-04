# GuestSneezeOS
[![Steam](https://img.shields.io/badge/steam-%23000000.svg?style=plastic&logo=steam&logoColor=white)](https://img.shields.io/badge/steam-%23000000.svg?style=plastic&logo=steam&logoColor=white)
[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white)](https://img.shields.io/badge/github-%23121011.svg?style=plastic&logo=github&logoColor=white)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=plastic&logo=linux&logoColor=black)](https://img.shields.io/badge/Linux-FCC624?style=plastic&logo=linux&logoColor=black)
![Release Package Number](https://release-badges-generator.vercel.app/api/releases.svg?user=GuestSneezeOS-Official&repo=GuestSneezeOS&gradient=ff6600,ffe500)
[![GuestSneezeOS](https://github.com/GuestSneezeOS-Official/GuestSneezeOS/assets/163439609/919e711f-a488-4b35-9581-5792b88a95f4)](https://guestsneezeos-official/guestsneezeos/releases)

# About
**GuestSneezeOS**, a [**Debian-based**](https://www.debian.org/derivatives/) Linux distribution inspired by [**The Other SteamOS Clones**](https://github.com/ChimeraOS/chimeraos/wiki/OS-Comparison), prioritizes performance and simplicity for gaming.Preinstalled with [Steam](https://steam.fandom.com/wiki/Steam), it offers access to a vast game library. With full access to [Debian](https://www.debian.org/) and [SteamOS](https://en.wikipedia.org/wiki/SteamOS) resources, users enjoy stable gaming experiences and access to a wide range of software. Moreover, GuestSneezeOS comes preinstalled with [Wine](https://www.winehq.org/) and [Discord](https://discord.com/), enhancing its versatility for gaming and communication needs. Its user-friendly interface and stability make it ideal for gamers on various hardware setups. **GuestSneezeOS** also offers a Lite version featuring the [**LXDE**](https://lxde.org) environment, providing users with a lightweight and efficient desktop experience tailored to modest hardware configurations and comes with the same things preinstalled with the main version but with a lighter desktop enviorment


# Requirements
- 1. UEFI Enable Firmware (not legacy)
- 2. At least 2GB of RAM
- 3. A semi-modern CPU (Dual Core)
- 4. An Intel Or AMD GPU (Nvidia Users Coming Soon)
- 5. At least an 8GB USB drive (for the installer)
- 6. At least 10GB of disk space (Main)

# Passwords
The Live ISO's Password is evolution (Why We Also Don't Know) 
<br>
How To Change It?
- Boot Into The Installer And Install it in "Text Mode" (This is the only supported format we have been able to install guestsneezeos successfully)
- Just Follow The Onscreen Instructions Then You Will See To Change The User,Root And Passwords

# Supported Grahics
AMD,Intel,Nvidia,VirtualBox,VMware,QEMU And Gnome Boxes

# Make Custom GuestSneezeOS Based ISO
- Open A Terminal Of An Installed Version GuestSneezeOS (Install the apps you want before doing this step)
- type in the terminal `sudo apt install curl` if curl is not installed
- then type `curl -fsSL https://pieroproietti.github.io/penguins-eggs-ppa/KEY.gpg | sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/penguins-eggs.gpg`
- then type `echo "deb [arch=$(dpkg --print-architecture)] https://pieroproietti.github.io/penguins-eggs-ppa ./" | sudo tee /etc/apt/sources.list.d/penguins-eggs.list > /dev/null`
- then type after that `sudo apt update`
- then type this `sudo apt install eggs`
- Then Type `sudo eggs produce --basename <NAME> --standard` Replace The `<NAME>` With The OS Name For A Liter ISO You Can Change It from `--standard` to `--max` but if you do that it will take longer (recommended on low system storage)
- The default username used by the `live` ISO in this case is `live`, and the password is `evolution`. The root password is the same, `evolution`.
- You Can Find The ISO On The `/home/eggs` folder in your system (also the source code will be there too)

# Authors
- GuestSneezePlayz (Project Leader)
- MinecraftToGo (Contributor)
- Xemulat (Contributor)
- pieroproietti (Creating The Penguin Eggs Project)
- The Debian Project (Creating The Debian Linux+GNU)
- You? (Contribute So We Can Stop Mistakes)
