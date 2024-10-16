# linux-ultrawide


# WHAT IS IT?

This is a custom compiled linux kernel for ultrawide monitors to fix the flicking in 5120x1440@240.00, or any other ultrawide issues with custom patches! The patch slowly clocks down the pixel rate.

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

# INSTALLATION:
Binary (Arch): sudo pacman -U linux-6.11.3.arch1-1-x86_64.pkg.tar.zst && sudo pacman -U linux-headers-6.11.3.arch1-1-x86_64.pkg.tar.zst 
