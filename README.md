<p align="center">
    <img width="420" src="https://i.imgur.com/QWqMIsr.png" alt="logo">
</p>

<h1 align="center">XeroLinux Source Code</h1>

<h2 align="center">💰 <a href="https://ko-fi.com/s/cf9def9630" target="_blank"><strong>Grab your copy here</strong></a> 💰</h2>

<p align="center">
    <img src="https://i.imgur.com/ejZ1ZQv.png" alt="logo">
</p>

<h2 align="center">🚀 Release notes 🚀</h2>

### GTK Theming

In case you use **GTK4/LibAdwaita** apps, you will have to Launch the toolkit from the dock, head on over to **Customization** select option `u` to apply the fix & update both GTK as well as KDE themes to latest versions from source. Only works for the default 🎨**Layan Theme**🎨.

### Included Features

Some features available via the toolkit were already applied on the ISO, since it was initially created for Vanilla Arch. Find the list of what has already been applied below :

<div align="center">

| XeroLinux                | Included Features       |
| ----------------------   | ----------------------  |
| ✅ PipeWire/Bluetooth    | ✅ Flatpak + Overrides  |
| ✅ Multithread Compiling | ✅ Chaotic-AUR Enabled  |
| ✅ Printer Driver        | ✅ Scanner Drivers      |
| ✅ Samba Tools           | ✅ XeroLinux Layan Rice |
| ✅ Fastfetch             | ✅ Oh-My-Posh           |

</div>

<h3 align="center">December 2024</h3>

This month's version includes a few changes and some minor fixes. See list below.

#### Chages/Fixes

- Kernel 6.12.1.
- KDE Plasma 6.2.4.
- QT Updated to 6.8.0.
- Fixed some services.
- Xero-Toolkit updated.
- Added reboot notifier.
- Stability improvements.
- Rice improvements/fixes.
- Restored Swap+/-Hibernate.
- Added missing KDE packages.
- Fixed Flatpak overrides. => [**Docs**](https://www.systutorials.com/docs/linux/man/1-flatpak-override/)

That's it for this month. Just make sure to update the system post-install before doing anything else for best experience.

<h3 align="center">November 2024</h3>

This month's version includes a few changes and some minor fixes. See list below.

#### Chages/Fixes

- Kernel 6.11.5.
- KDE Plasma 6.2.2.
- QT Updated to 6.8.0.
- Initramfs build fixed.
- Xero SDDM Theme fixed.
- SDDM onscreen keyboard.
- Onboard floating Keyboard.
- Removed Xero-Hooks (Not needed).

That's it for this month. Just make sure to update the system post-install before doing anything else for best experience.

<h3 align="center">October 2024</h3>

This month's version includes a few changes and some minor fixes. See list below.

#### Chages/Fixes

- Kernel 6.11.1.
- KDE Plasma 6.1.5.
- QT Updated to 6.7.3.
- Switched to `paru-git`.
- Toolkit updated to latest.
- Removed broadcom-wl-dkms.
- Added Preload for faster app loading.
- Pacman/conf updated with containerization.

That's it for this month. Just make sure to update the system post-install before doing anything else for best experience.

<h3 align="center">September 2024</h3>

This month's version includes a few major changes and minor fixes. See list below. ISO will boot using **SystemD-Boot** for Live Environment, however it will still be using **Grub** on the installed system.

#### Chages/Fixes

- Added a Paru config.
- Bios/MBR Boot has been fixed.
- Updated Dolphin Context Menus.
- Tailscale can be installed via toolkit.
- Increased `/boot/` partition size to 2GiB.
- Disabled Swap+/-Hibernate In Calamares.✴️
- Removed Hybrid GPU Support from toolkit.

✴️ **Swap + Hibernate**

You can still select Swap File in case you need it. Only use it if you are low on RAM (8GB or lower) otherwise would be a waste of space.

<h3 align="center">August 2024 (Initial Release)</h3>

This initial release only boots on **EFI** machines, **Legacy Boot** is broken. Make sure you use it on a modern *EFI* system.
