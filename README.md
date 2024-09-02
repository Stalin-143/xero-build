<p align="center">
    <img width="420" src="https://i.imgur.com/QWqMIsr.png" alt="logo">
</p>

<h1 align="center">!!! XeroLinux ISO Source Code !!!!</h1>

<p align="center">
    <img src="https://i.imgur.com/ejZ1ZQv.png" alt="logo">
</p>

<h2 align="center">🚀 Release notes 🚀</h2>

### GTK Theming

In case you use **GTK4/LibAdwaita** apps, you will have to Launch the toolkit from the dock, head on over to **4. Customization** select option `u` to apply the fix & update both GTK as well as KDE themes to latest versions from source. Only works for the default 🎨**Layan Theme**🎨.

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

<h3 align="center">September 2024</h3>

This month's version includes a few major changes and minor fixes. See list below. ISO will boot using **SystemD-Boot** for Live Environment, however it will still be using **Grub** on the installed system. Please use **Ventoy** for a better experience...

#### Major Fixes

- ISO uses SystemD-Boot now.
- Bios/MBR Boot has been fixed.
- Fixed some services not starting.
- Tailscale can be installed via toolkit.
- Disabled Swap+/-Hibernate In Calamares.✴️
- Removed Hybrid GPU Support from toolkit.

✴️ **Swap + Hibernate**

I am currently reworking this option. Due to that, it's been disabled. Will be reactivated once work is done on the next ISO. Until then you can still select Swap File in case you need it. Only use it if you are low on RAM (8GB or lower) otherwise would be a waste of space. Thanks for your understanding.

#### Minor tweaks

- Added a Paru config.
- Updated XeroLinux Toolkit.
- Kernel updated to v6.10.7.
- Updated Calamares to latest.
- Minor Wayland fixes included.
- Updated Dolphin Context Menus.

<h3 align="center">August 2024 (Initial Release)</h3>

This initial release currently only boots on **EFI** machines, **Legacy Boot** is currently broken. Make sure you use it on a modern *EFI* system.


