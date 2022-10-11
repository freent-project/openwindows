# OpenWindows 11
OpenWindows is a project to create a free Windows operating system made out of these components:
* **Bootloader:** The bootloader is responsible for booting OpenWindows.
* **Kernel:** The kernel is the most important part. OpenWindows does not use Microsoft's
  NT kernel, but rather it's own open-source NT kernel.
* **Platform:** The OpenWindows platform is a platform to make sure all OpenWindows developers
  have brief understanding
* **Installer (Part 1):** Part 1 of the installer installs all required files for part 2.
* **Installer (Part 2):** Part 2 of the installer installs all of the tools, games, etc.
* **Linusti:** Linusti is a reimplementation of WSL to run programs designed for the Linux
  Kernel on OpenWindows. No dual-boot required.
  * **LinustiG:** A Wayland server with PulseAudio and XWayland. Run graphical Linux
    Kernel programs.
## Installation
> **Warning**: Installation of OpenWindows will delete **all** data, including files,
  apps, settings, passwords, etc. Back-up your current OS before continuing.

> **Info**: Installation of OpenWindows requires an NTFS partition with a Windows-style
  drive letter. OpenWindows cannot recgonise any other partition.

For instructions on installing OpenWindows, see [the guide at the OpenWindows documentation][docs].
This guide is split into different sections, so carefully read each step and do not skip
any steps unless the guide asks you to.

 [docs]: https://freent-project.github.com/openwindows-docs/install
