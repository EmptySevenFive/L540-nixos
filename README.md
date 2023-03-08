# Student-Nixos
NixOS .dot Configuration files for Lenovo L540 Laptop, or any other machine.

Quick install of a standard nixos machine with a graphical display manager.

Default user "Student"

Based on work by willmcpherson2/willos, and samuela/nixos-up

The intention is to teach or demonstrate to students different filesystem layouts and package management for various linux flavours.

## Installation:

Boot a live/installer for nixos, 
Enable networking,
issue the following command.


```
sudo nix-shell https://github.com/emptysevenfive/Student-Nixos/archive/main.tar.gz
```

When asked for disk... enter /dev/sda

When asked enter password for default user: student

Enable/Disable root user in default.nix

If enabled last step is to set root password.

