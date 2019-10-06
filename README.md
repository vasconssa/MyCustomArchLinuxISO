# MyCustomArchLinuxISO
Custom Arch Linux ISO for maintenance

### Prerequisites

A work archlinux enviroment, it work chrooting with [arch-bootstrap](https://github.com/tokland/arch-bootstrap)

```
Give examples
```

### Installing

Follow the [Archiso](https://wiki.archlinux.org/index.php/archiso) wiki, and customize installation and build de iso image using:

```
./build.sh -v
```

after that cp the iso to an usb disk:

```
dd BS=4M if=image.iso out=/dev/sdx status=progress oflag=sync
```

## My Customization
The main customizations are:
**Shell:** zsh

**Window Manager:** i3-gaps

**Editor:** vim - contains my current vim config and plugins


