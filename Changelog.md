<h2 align="center">!!! XeroLinux Changelog !!!!</h2>

I have been following up on all issues reported on Discord. If you notice any, please I urge you to let me know, otherwise I won't be able to fix them. It's up to you. I can't fix what I do not see. Distro will only evolve thanks to all of you. Thanks.

<h3 align="center">September 2024</h3>

This month's version includes a few major changes and minor fixes. See list below. ISO will boot using **SystemD-Boot** for Live Environment, however it will still be using **Grub** on the installed system. Please use **Ventoy** for a better experience...

#### Major Fixes

- ISO uses SystemD-Boot now.
- Bios/MBR Boot mode fixed now.
- Fixed some services not starting.

#### Minor tweaks

- Updated XeroLinux Toolkit.
- Kernel updated to v6.10.6.
- Updated Calamares to latest.
- Minor Wayland fixes included.
- Updated Dolphin Context Menus.

⚠️ **Calamares Qt6 Issue** ⚠️

In case the **Calamares Installer** crashes during install, just reboot the Live ISO and try installing again, it should work fine. There's minor issue with latest **Qt6** libraries.

<h3 align="center">August 2024</h3>

**This is the initial release date.**

As you can see, after thinking long and hard, I have decided to revive the Distro as an easy alternative to the [**PlasmaInstall**](https://xerolinux.xyz/news/xerolinux-plasma/) script. No major changes have been added. Just some quality of life ones. It's still the Distro you have grown to love throughout the years.

#### Included Features

Some features available via the toolkit were already applied on the ISO, since it was initially created for Vanilla Arch. Find the list of what has already been applied below :

✅ PipeWire/Bluetooth<br>
✅ Flatpak + Overrides<br>
✅ Multithread Compiling<br>
✅ Chaotic-AUR Enabled<br>
✅ Printer Driver/Tools<br>
✅ Samba Tools and configs<br>
✅ Scanner Driver/Tools<br>
✅ Fastfetch/OhMyPosh<br>
✅ XeroLinux Layan Rice

### Issues + Fixes

- ⚠️ **Theming Issue** ⚠️

There might be a small issue with **GTK4/LibAdwaita** app theming, I couldn't find a workaround. In case you use those, you will have to Launch the toolkit from the dock, head on over to **4. Customization** select option `u` to apply the fix & update both GTK as well as KDE themes to latest versions from source.

![Fix](https://i.imgur.com/cBVO4ki.png)

The included fix only works for the default 🎨**Layan Theme**🎨, if you use another, well, you will have to ask its dev for patch, not all themes work for **GTK4/LibAdwaita** apps since Devs are mostly anti-theming.

- ⚠️ **Tailscale Issue** ⚠️

If you use [**Tailscale**](https://tailscale.com), you will need to install it via the toolkit as well. Issue is that since this is a custom distro, official installer will not be able to recognize it unless devs add it.

![TSFix](https://i.imgur.com/ZFbFfsL.png)

While I have requested this, in the meantime, you will need to launch toolkit, choose option **2. System Drivers** then >> **5. Tailscale w/XeroLinux fix** (name might change) as seen in the image above and install it from there. That's it, **Tailscale** will successfully install. Just make sure you reboot the system once it's done for the service to run.
