# LubuMaster DOWNLOAD: [OVA](https://github.com/Virtual-Machines/LubuMaster/releases/download/latest/LubuMaster.ova) - [ISO](https://github.com/Virtual-Machines/LubuMaster/releases/download/latest/LubuMaster.iso)
Last update: 2019-07-14

LubuMaster is "an experimental Lubuntu 18.04.2 based distro that builds custom distributions"

Generating live environment on virtual machine (using the OVA):

![LubuMasterBuild](https://raw.githubusercontent.com/Virtual-Machines/LubuMaster/master/LubuMasterBuild.png)


Test the liveCD (included as ISO):

![LubuMasterLive](https://raw.githubusercontent.com/Virtual-Machines/LubuMaster/master/LubuMasterLive.png)

- Minimal Lubuntu Bionic 18.04.2 (lubuntu-core package)
- Linux Kernel 4.18 HWE (Hardware Enablement)
- VirtualBox Guest Additions (bidirectional clipboard between host and guest, shared folders capable, Seamless Mode...)
- [Pinguy Builder](https://pinguyos.com/2015/09/pinguy-builder-an-app-to-backupremix-buntu/)
- Synaptic package manager
- Basic python http server included. Example: python3 -m http.server 8080
- Command-line download manager: wget
- NAT port forwarding configured on 8080 that allows web browser testing outside virtual machine
- It can be used as a base of development environments, to test software...
- OVA and ISO files less than 500 MB
- User and pass of system is the same: lubuntu
- Import OVA on VirtualBox using "File -> Import Appliance (or Control + I)"
