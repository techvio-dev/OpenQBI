# OpenQBI
OpenQBI (Aka Open QEMU Battery Indicator) is a workaround to be able to report battery levels to QEMU virtual machines.

QEMU lacks an important function which is reporting batter levels to virtual machines. Here is where OpenQBI comes in.

# Current progress/plan:
- Working on a simple model to report battery information through a simple tray application.
- For now, I will develop a solution for Windows virtual machines, and then extend it to other operating systems.

# Long-term plans:
- Making the guest virtual machine detect the battery on the low level, like "Report Battery Information in the Guest" on VMWare Workstation.
- Integrating this functionality into QEMU.
