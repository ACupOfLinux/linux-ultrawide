# linux-ultrawide


# WHAT IS IT?

This is a custom compiled linux kernel for ultrawide monitors to fix the flicking in 5120x1440@240.00, or any other ultrawide issues with custom patches! The patch clocks the pixel rate down from what i'm aware.


# INSTALLATION:
Binary (Arch): 
```console
sudo pacman -U linux-6.11.3.arch1-1-x86_64.pkg.tar.zst && sudo pacman -U linux-headers-6.11.3.arch1-1-x86_64.pkg.tar.zst
```

Binary (Distro Agnostic) COMING SOON!:
```console
sudo cp -v BzImage /boot/vmlinuz-linux && sudo cp System.Map /boot && sudo mkinitcpio -p linux -g /boot/initramfs-linux.img
```

Building The Kernel (No need to configure unless REALLY needed):
```console
sudo make -j{YOUR NUMBER OF CPU THREADS +1} && sudo make -j{YOUR NUMBER OF CPU THREADS +1} modules_install
```

Linux kernel
============

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the reStructuredText markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.

# CREDIT:
Gitlab User: @robertswiecki
