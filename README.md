
#  I2C RTC DS1307 boot scripts for Raspberry Pi (for Arch Linux ARM)

These scripts load and initiate I2C DS1307 RTC module as a hardware clock in arch linux arm on every boot. These can be packaged as arch linux package using `makepkg` in `build-devel`.

It's available on the [AUR](https://wiki.archlinux.org/title/Arch_User_Repository) as [raspberrypi-rtc-ds1307](https://aur.archlinux.org/packages/raspberrypi-rtc-ds1307/) and can be easily installed using an AUR helper like [PARU](https://github.com/Morganamilo/paru),

```bash
paru -S raspberrypi-rtc-ds1307
```

##  Building

This can be packaged for arch linux using,

```bash
makepkg -si
```

##  Installing

The built package can be installed on arch linux by,

```bash
sudo pacman -U raspberrypi-rtc-ds1307-0.1-1-aarch64.pkg.tar.xz
```

##  License
This project is under [MIT License](LICENSE)
