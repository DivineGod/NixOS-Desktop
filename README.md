# NixOS-Desktop

This is a backup of an experiment to daily drive nixos on my AMD Desktop.

I don't yet know if I actually liked using it this way.

This backup just serves as a point to start back up from, if I need to.

## OS

The os is defined as a flake so changing things needs to run

```bash
 sudo nixos-rebuild switch --flake /etc/nixos/#nixos
 ```

## Home Manager

in the `home` sub-directory is the home manager configuration.

Make changes and use

```bash
home-manager switch
```

to apply changes
