AUR
===

My ArchLinux AUR


HOWTO BUILD
===========

Use tinc-pre-systemd for example.

# Generate checksum
cd tinc-pre-systemd
makepkg -g >> PKGBUILD

# Build package
makepkg

# Verify the package
namcap namcap tinc-pre-systemd-1-1-any.pkg.tar.xz
