# Installation

<img src="./assets/installation.png" width="50">

**Note**: Linutil can be run directly from the command line using the `CLI` installation. It is also available in different packages and can be installed via `Cargo`.

- [CLI](#cli)
- [Packages](#package)
    - [Arch Linux](#arch-linux)
    - [OpenSUSE](#opensuse)
    - [Cargo](#cargo)

## CLI 

<strong> *To get started, pick which branch you would like to use, then run the command in your terminal:* </strong>

### Stable Branch (Recommended)
```bash
curl -fsSL https://christitus.com/linux | sh
```
### Dev branch
```bash
curl -fsSL https://christitus.com/linuxdev | sh
```

## Package 

<strong> *Linutil is also available as a package in various repositories:* </strong>

[![Packaging status](https://repology.org/badge/vertical-allrepos/linutil.svg)](https://repology.org/project/linutil/versions)

### Arch Linux

Linutil can be installed on [Arch Linux](https://archlinux.org) with three different [AUR](https://aur.archlinux.org) packages:

- `linutil` - Stable release compiled from source
- `linutil-bin` - Stable release pre-compiled
- `linutil-git` - Compiled from the last commit (not recommended)

by running:

```bash
git clone https://aur.archlinux.org/<package>.git
cd <package>
makepkg -si
```

Replace `<package>` with your preferred package.

*If you use [yay](https://github.com/Jguer/yay), [paru](https://github.com/Morganamilo/paru) or any other [AUR Helper](https://wiki.archlinux.org/title/AUR_helpers), it's even simpler:*

```bash
paru -S linutil
```

Replace `paru` with your preferred helper and `linutil` with your preferred package.

### OpenSUSE
  
Linutil can be installed on OpenSUSE with:
```bash
sudo zypper install linutil
```

### Cargo

[![Crates.io Version](https://img.shields.io/crates/v/linutil_tui?style=for-the-badge&color=%23af3a03)](https://crates.io/crates/linutil_tui)

Linutil can be installed via [Cargo](https://doc.rust-lang.org/cargo) with:

```bash
cargo install linutil_tui
```

<strong> *Note that crates installed using `cargo install` require manual updating with `cargo install --force` (update functionality is [included in LinUtil](https://christitustech.github.io/linutil/userguide/#applications-setup))* </strong>


