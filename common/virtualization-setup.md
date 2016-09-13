## Common  Setup Instructions
#### Softwares

  * Virtualbox
  * Vagrant
  * Git
  * Atom
  * ConEMU
  
====================


### Systems Preparation

Participants will have to create Virtual Machines with VirtualBox + Vagrant and setup the learning environment. Vagrant is a tool which allows us to build, configure and setup portable virtual machines automatically, and it works with multitude of hypervisors and cloud platforms (AWS etc.), Virtualbox included. We would also need a sophisticated  editor with chef plugin, which would help us write code fast, with auto completion and syntax highlighting features etc. Thats where Atom comes in handy.

On windows systems, utilities such as ssh do not come installed by default. To install a bash shell and create a remote terminal, Git and ConEmu are effective tools.


#### Enabling Virtualization from BIOS

In order to run 64bit VMs, systems need to be enabled with hardware virtualization extensions. On a Mac OSX, this is typically enabled by default. However, on many Windows Laptops/Desktops, VT-x needs to be manually enabled.

[Enable Hardware Virtualization Technology(VT -x) from BIOS](https://docs.fedoraproject.org/en-US/Fedora/13/html/Virtualization_Guide/sect-Virtualization-Troubleshooting-Enabling_Intel_VT_and_AMD_V_virtualization_hardware_extensions_in_BIOS.html)

These instructions different from system to system, bases on the BIOS provided with your laptop/desktop. For a lot of systems, Virtualization options are found in **Security** tab.

